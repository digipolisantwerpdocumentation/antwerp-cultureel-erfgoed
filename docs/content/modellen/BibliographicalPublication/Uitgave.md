```mermaid
graph LR
0c5885fc-66a9-11ee-974d-00163e71351b["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|0c588c3c-66a9-11ee-974d-00163e71351b(rdfs:Literal)
0c588e8a-66a9-11ee-974d-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|0c58901a-66a9-11ee-974d-00163e71351b(xsd:string)
8d23ca72-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|8d23ce14-424e-11ee-b0c4-00163e71351b(rdfs:Literal)
8d23cf40-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|8d23d03a-424e-11ee-b0c4-00163e71351b(xsd:string)
d77d0958-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|d77d0d22-424e-11ee-b0c4-00163e71351b(rdfs:Literal)
d77d0e58-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|d77d0f5c-424e-11ee-b0c4-00163e71351b(xsd:string)
f434affc-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]-->|"crm:P82a_begin_of_the_begin"|f434b2ae-04f9-11ee-9497-96a6d2455259(rdfs:Literal)
f434affc-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]-->|"crm:P82b_end_of_the_end"|f434b538-04f9-11ee-9497-96a6d2455259(rdfs:Literal)
f434b2f4-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"rdfs:label"|f434c55a-04f9-11ee-9497-96a6d2455259(xsd:string)
f434b57e-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]-->|"rdfs:label"|f434b68c-04f9-11ee-9497-96a6d2455259(xsd:string)
f434b5c4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"rdfs:label"|f434ba38-04f9-11ee-9497-96a6d2455259(xsd:string)
0c5885fc-66a9-11ee-974d-00163e71351b["crm:E41_Appellation"]-->|"crm:P2_has_type"|0c588e8a-66a9-11ee-974d-00163e71351b["crm:E55_Type"]
8d23ca72-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P2_has_type"|8d23cf40-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]
d77d0958-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P2_has_type"|d77d0e58-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]
f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]-->|"crm:P01i_is_domain_of"|f434b060-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]
f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]-->|"crm:P4_has_time-span"|f434affc-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]
f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]-->|"crm:P7_took_place_at"|f434b57e-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]
f434b060-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]-->|"crm:P02_has_range"|f434b5c4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]
f434b060-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]-->|"crm:P14.1_in_the_role_of"|f434b2f4-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]
f434b57e-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]-->|"crm:P1_is_identified_by"|8d23ca72-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]
f434b5c4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"crm:P1_is_identified_by"|0c5885fc-66a9-11ee-974d-00163e71351b["crm:E41_Appellation"]
f434b5c4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"crm:P1_is_identified_by"|d77d0958-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]
f434b650-04f9-11ee-9497-96a6d2455259["frbr:F24_Publication_Expression"]-->|"frbr:R24i_was_created_through"|f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]
style 0c588c3c-66a9-11ee-974d-00163e71351b_s stroke-dasharray: 5
style 0c588e8a-66a9-11ee-974d-00163e71351b_s stroke-dasharray: 5
style 8d23ce14-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style 8d23cf40-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style d77d0d22-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style d77d0e58-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style f434b060-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434affc-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b57e-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b2ae-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b538-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b5c4-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b2f4-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style 8d23ca72-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style 0c5885fc-66a9-11ee-974d-00163e71351b_s stroke-dasharray: 5
style d77d0958-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style f434a6e2-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
0c588c3c-66a9-11ee-974d-00163e71351b["rdfs:Literal"]-.-0c588c3c-66a9-11ee-974d-00163e71351b_s(["Uitgever extensie inhoud"])
0c588e8a-66a9-11ee-974d-00163e71351b["crm:E55_Type"]-.-0c588e8a-66a9-11ee-974d-00163e71351b_s(["Uitgever extensie type URI"])
8d23ce14-424e-11ee-b0c4-00163e71351b["rdfs:Literal"]-.-8d23ce14-424e-11ee-b0c4-00163e71351b_s(["Uitgave plaats naam inhoud"])
8d23cf40-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]-.-8d23cf40-424e-11ee-b0c4-00163e71351b_s(["Uitgave plaats naam type URI"])
d77d0d22-424e-11ee-b0c4-00163e71351b["rdfs:Literal"]-.-d77d0d22-424e-11ee-b0c4-00163e71351b_s(["Publicatiegebeurtenis rol agent naam toevoeging inhoud"])
d77d0e58-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]-.-d77d0e58-424e-11ee-b0c4-00163e71351b_s(["Publicatiegebeurtenis rol agent naam type uri"])
f434b060-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]-.-f434b060-04f9-11ee-9497-96a6d2455259_s(["Uitgever rol"])
f434affc-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]-.-f434affc-04f9-11ee-9497-96a6d2455259_s(["Uitgave jaar"])
f434b57e-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]-.-f434b57e-04f9-11ee-9497-96a6d2455259_s(["Uitgave plaats URI"])
f434b2ae-04f9-11ee-9497-96a6d2455259["rdfs:Literal"]-.-f434b2ae-04f9-11ee-9497-96a6d2455259_s(["Uitgave jaar begin"])
f434b538-04f9-11ee-9497-96a6d2455259["rdfs:Literal"]-.-f434b538-04f9-11ee-9497-96a6d2455259_s(["Uitgave jaar einde"])
f434b5c4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-.-f434b5c4-04f9-11ee-9497-96a6d2455259_s(["Uitgever URI"])
f434b2f4-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-.-f434b2f4-04f9-11ee-9497-96a6d2455259_s(["Uitgever rol URI"])
8d23ca72-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-.-8d23ca72-424e-11ee-b0c4-00163e71351b_s(["Uitgave plaats naam"])
0c5885fc-66a9-11ee-974d-00163e71351b["crm:E41_Appellation"]-.-0c5885fc-66a9-11ee-974d-00163e71351b_s(["Uitgever extensie"])
d77d0958-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-.-d77d0958-424e-11ee-b0c4-00163e71351b_s(["Publicatiegebeurtenis rol agent naam"])
f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]-.-f434a6e2-04f9-11ee-9497-96a6d2455259_s(["Uitgave plaats"])
style 0c5885fc-66a9-11ee-974d-00163e71351b fill:#EEE8AA
style 0c588c3c-66a9-11ee-974d-00163e71351b fill:#D3D3D3
style 0c588e8a-66a9-11ee-974d-00163e71351b fill:#ffa500
style 0c58901a-66a9-11ee-974d-00163e71351b fill:#D3D3D3
style 8d23ca72-424e-11ee-b0c4-00163e71351b fill:#EEE8AA
style 8d23ce14-424e-11ee-b0c4-00163e71351b fill:#D3D3D3
style 8d23cf40-424e-11ee-b0c4-00163e71351b fill:#ffa500
style 8d23d03a-424e-11ee-b0c4-00163e71351b fill:#D3D3D3
style d77d0958-424e-11ee-b0c4-00163e71351b fill:#EEE8AA
style d77d0d22-424e-11ee-b0c4-00163e71351b fill:#D3D3D3
style d77d0e58-424e-11ee-b0c4-00163e71351b fill:#ffa500
style d77d0f5c-424e-11ee-b0c4-00163e71351b fill:#D3D3D3
style f434a6e2-04f9-11ee-9497-96a6d2455259 fill:#5DAEEC
style f434affc-04f9-11ee-9497-96a6d2455259 fill:#76A5AF
style f434b060-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434b2ae-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434b2f4-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434b538-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434b57e-04f9-11ee-9497-96a6d2455259 fill:#8CBF76
style f434b5c4-04f9-11ee-9497-96a6d2455259 fill:#ffc0cb
style f434b68c-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434ba38-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434c55a-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
```
