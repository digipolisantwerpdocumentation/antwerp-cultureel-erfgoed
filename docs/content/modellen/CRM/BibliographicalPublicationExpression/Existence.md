```mermaid
graph LR
14d70cca-4256-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P2_has_type"|14d711ac-4256-11ee-b0c4-00163e71351b["crm:E55_Type"]
2bae605a-4257-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P2_has_type"|2bae6758-4257-11ee-b0c4-00163e71351b["crm:E55_Type"]
8d23ca72-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P2_has_type"|8d23cf40-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]
8e8e330e-4256-11ee-bc5c-00163e71351b["crm:E41_Appellation"]-->|"crm:P2_has_type"|8e8e3818-4256-11ee-bc5c-00163e71351b["crm:E55_Type"]
b3d2c494-424d-11ee-974d-00163e71351b["crm:E41_Appellation"]-->|"crm:P2_has_type"|b3d2cf84-424d-11ee-974d-00163e71351b["crm:E55_Type"]
d77d0958-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P2_has_type"|d77d0e58-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]
f4349fc6-04f9-11ee-9497-96a6d2455259["frbr:F28_Expression_Creation"]-->|"crm:P01i_is_domain_of"|f434beac-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]
f4349fc6-04f9-11ee-9497-96a6d2455259["frbr:F28_Expression_Creation"]-->|"crm:P14_carried_out_by"|f434bb0a-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]
f4349fc6-04f9-11ee-9497-96a6d2455259["frbr:F28_Expression_Creation"]-->|"crm:P32_used_general_technique"|f434bbe6-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]
f4349fc6-04f9-11ee-9497-96a6d2455259["frbr:F28_Expression_Creation"]-->|"crm:P4_has_time-span"|f434bdd0-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]
f4349fc6-04f9-11ee-9497-96a6d2455259["frbr:F28_Expression_Creation"]-->|"crm:P7_took_place_at"|f434bb50-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]
f4349fc6-04f9-11ee-9497-96a6d2455259["frbr:F28_Expression_Creation"]-->|"crm:P94_has_created"|f434cec4-04f9-11ee-9497-96a6d2455259["crm:E33_Linguistic_Object"]
f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]-->|"crm:P01i_is_domain_of"|f434b060-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]
f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]-->|"crm:P14_carried_out_by"|f434bac4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]
f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]-->|"crm:P32_used_general_technique"|f434cf0a-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]
f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]-->|"crm:P4_has_time-span"|f434affc-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]
f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]-->|"crm:P7_took_place_at"|f434b57e-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]
f434b060-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]-->|"crm:P02_has_range"|f434b5c4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]
f434b060-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]-->|"crm:P14.1_in_the_role_of"|f434b2f4-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]
f434b57e-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]-->|"crm:P1_is_identified_by"|8d23ca72-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]
f434b5c4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"crm:P1_is_identified_by"|d77d0958-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]
f434b650-04f9-11ee-9497-96a6d2455259["frbr:F24_Publication_Expression"]-->|"frbr:R17i_was_created_by"|f4349fc6-04f9-11ee-9497-96a6d2455259["frbr:F28_Expression_Creation"]
f434b650-04f9-11ee-9497-96a6d2455259["frbr:F24_Publication_Expression"]-->|"frbr:R24i_was_created_through"|f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]
f434bac4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"crm:P1_is_identified_by"|b3d2c494-424d-11ee-974d-00163e71351b["crm:E41_Appellation"]
f434bb0a-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"crm:P1_is_identified_by"|8e8e330e-4256-11ee-bc5c-00163e71351b["crm:E41_Appellation"]
f434bb50-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]-->|"crm:P1_is_identified_by"|14d70cca-4256-11ee-b0c4-00163e71351b["crm:E41_Appellation"]
f434be16-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"crm:P1_is_identified_by"|2bae605a-4257-11ee-b0c4-00163e71351b["crm:E41_Appellation"]
f434beac-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]-->|"crm:P02_has_range"|f434be16-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]
f434beac-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]-->|"crm:P14.1_in_the_role_of"|f434bd8a-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]
f434cec4-04f9-11ee-9497-96a6d2455259["crm:E33_Linguistic_Object"]-->|"crm:P72_has_language"|f434b0b0-04f9-11ee-9497-96a6d2455259["crm:E56_Language"]
14d70cca-4256-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|14d7106c-4256-11ee-b0c4-00163e71351b(rdfs:Literal)
14d711ac-4256-11ee-b0c4-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|14d712a6-4256-11ee-b0c4-00163e71351b(xsd:string)
2bae605a-4257-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|2bae65a0-4257-11ee-b0c4-00163e71351b(rdfs:Literal)
2bae6758-4257-11ee-b0c4-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|2bae68d4-4257-11ee-b0c4-00163e71351b(xsd:string)
8d23ca72-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|8d23ce14-424e-11ee-b0c4-00163e71351b(rdfs:Literal)
8d23cf40-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|8d23d03a-424e-11ee-b0c4-00163e71351b(xsd:string)
8e8e330e-4256-11ee-bc5c-00163e71351b["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|8e8e36ce-4256-11ee-bc5c-00163e71351b(rdfs:Literal)
8e8e3818-4256-11ee-bc5c-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|8e8e3908-4256-11ee-bc5c-00163e71351b(xsd:string)
b3d2c494-424d-11ee-974d-00163e71351b["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|b3d2ccbe-424d-11ee-974d-00163e71351b(rdfs:Literal)
b3d2cf84-424d-11ee-974d-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|b3d2d1dc-424d-11ee-974d-00163e71351b(xsd:string)
d77d0958-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|d77d0d22-424e-11ee-b0c4-00163e71351b(rdfs:Literal)
d77d0e58-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|d77d0f5c-424e-11ee-b0c4-00163e71351b(xsd:string)
f434affc-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]-->|"crm:P82a_begin_of_the_begin"|f434b2ae-04f9-11ee-9497-96a6d2455259(rdfs:Literal)
f434affc-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]-->|"crm:P82b_end_of_the_end"|f434b538-04f9-11ee-9497-96a6d2455259(rdfs:Literal)
f434b0b0-04f9-11ee-9497-96a6d2455259["crm:E56_Language"]-->|"rdfs:label"|fe246a5e-4bc4-11ee-b0c4-00163e71351b(xsd:string)
f434b2f4-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"rdfs:label"|f434c55a-04f9-11ee-9497-96a6d2455259(xsd:string)
f434b57e-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]-->|"rdfs:label"|f434b68c-04f9-11ee-9497-96a6d2455259(xsd:string)
f434b5c4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"rdfs:label"|f434ba38-04f9-11ee-9497-96a6d2455259(xsd:string)
f434bac4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"rdfs:label"|f434c514-04f9-11ee-9497-96a6d2455259(xsd:string)
f434bb0a-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"rdfs:label"|f434bcfe-04f9-11ee-9497-96a6d2455259(xsd:string)
f434bb50-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]-->|"rdfs:label"|f434bba0-04f9-11ee-9497-96a6d2455259(xsd:string)
f434bbe6-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"rdfs:label"|f434bd44-04f9-11ee-9497-96a6d2455259(xsd:string)
f434bd8a-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"rdfs:label"|f434bc72-04f9-11ee-9497-96a6d2455259(xsd:string)
f434bdd0-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]-->|"crm:P82a_begin_of_the_begin"|f434bcb8-04f9-11ee-9497-96a6d2455259(rdfs:Literal)
f434bdd0-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]-->|"crm:P82b_end_of_the_end"|f434be66-04f9-11ee-9497-96a6d2455259(rdfs:Literal)
f434be16-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"rdfs:label"|f434bc22-04f9-11ee-9497-96a6d2455259(xsd:string)
f434cf0a-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"rdfs:label"|f434d216-04f9-11ee-9497-96a6d2455259(xsd:string)
14d7106c-4256-11ee-b0c4-00163e71351b["rdfs:Literal"]-.-14d7106c-4256-11ee-b0c4-00163e71351b_s(["Expression Creation Place Appellation Content"])
14d711ac-4256-11ee-b0c4-00163e71351b["crm:E55_Type"]-.-14d711ac-4256-11ee-b0c4-00163e71351b_s(["Expression Creation Place Appellation Type"])
2bae65a0-4257-11ee-b0c4-00163e71351b["rdfs:Literal"]-.-2bae65a0-4257-11ee-b0c4-00163e71351b_s(["Expression Creation Role Actor Appellation Content"])
2bae6758-4257-11ee-b0c4-00163e71351b["crm:E55_Type"]-.-2bae6758-4257-11ee-b0c4-00163e71351b_s(["Expression Creation Role Actor Appellation Type"])
8d23ce14-424e-11ee-b0c4-00163e71351b["rdfs:Literal"]-.-8d23ce14-424e-11ee-b0c4-00163e71351b_s(["Publication Event Place Appellation Content"])
8d23cf40-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]-.-8d23cf40-424e-11ee-b0c4-00163e71351b_s(["Publication Event Place Appellation Type"])
8e8e36ce-4256-11ee-bc5c-00163e71351b["rdfs:Literal"]-.-8e8e36ce-4256-11ee-bc5c-00163e71351b_s(["Expression Creation Actor Appellation Content"])
8e8e3818-4256-11ee-bc5c-00163e71351b["crm:E55_Type"]-.-8e8e3818-4256-11ee-bc5c-00163e71351b_s(["Expression Creation Actor Appellation Type"])
b3d2ccbe-424d-11ee-974d-00163e71351b["rdfs:Literal"]-.-b3d2ccbe-424d-11ee-974d-00163e71351b_s(["Publication Event Actor Appellation Content"])
b3d2cf84-424d-11ee-974d-00163e71351b["crm:E55_Type"]-.-b3d2cf84-424d-11ee-974d-00163e71351b_s(["Publication Event Actor Appellation Type"])
d77d0d22-424e-11ee-b0c4-00163e71351b["rdfs:Literal"]-.-d77d0d22-424e-11ee-b0c4-00163e71351b_s(["Publication Event Role Actor Appellation Content"])
d77d0e58-424e-11ee-b0c4-00163e71351b["crm:E55_Type"]-.-d77d0e58-424e-11ee-b0c4-00163e71351b_s(["Publication Event Role Actor Appellation Type"])
f434beac-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]-.-f434beac-04f9-11ee-9497-96a6d2455259_s(["Expression Creation Role"])
f434bb0a-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-.-f434bb0a-04f9-11ee-9497-96a6d2455259_s(["Expression Creation Actor"])
f434bbe6-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-.-f434bbe6-04f9-11ee-9497-96a6d2455259_s(["Expression Creation Technique Type"])
f434bdd0-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]-.-f434bdd0-04f9-11ee-9497-96a6d2455259_s(["Expression Creation Time-Span"])
f434bb50-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]-.-f434bb50-04f9-11ee-9497-96a6d2455259_s(["Expression Creation Place"])
f434cec4-04f9-11ee-9497-96a6d2455259["crm:E33_Linguistic_Object"]-.-f434cec4-04f9-11ee-9497-96a6d2455259_s(["Expression Creation Linguistic Object"])
f434b060-04f9-11ee-9497-96a6d2455259["crm:PC14_carried_out_by"]-.-f434b060-04f9-11ee-9497-96a6d2455259_s(["Publication Event Role"])
f434bac4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-.-f434bac4-04f9-11ee-9497-96a6d2455259_s(["Publication Event Actor"])
f434cf0a-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-.-f434cf0a-04f9-11ee-9497-96a6d2455259_s(["Publication Event Technique Type"])
f434affc-04f9-11ee-9497-96a6d2455259["crm:E52_Time-Span"]-.-f434affc-04f9-11ee-9497-96a6d2455259_s(["Publication Event Time-Span"])
f434b57e-04f9-11ee-9497-96a6d2455259["crm:E53_Place"]-.-f434b57e-04f9-11ee-9497-96a6d2455259_s(["Publication Event Place"])
f434b2ae-04f9-11ee-9497-96a6d2455259["rdfs:Literal"]-.-f434b2ae-04f9-11ee-9497-96a6d2455259_s(["Publication Event Time-Span Begin"])
f434b538-04f9-11ee-9497-96a6d2455259["rdfs:Literal"]-.-f434b538-04f9-11ee-9497-96a6d2455259_s(["Publication Event Time-Span End"])
f434b5c4-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-.-f434b5c4-04f9-11ee-9497-96a6d2455259_s(["Publication Event Role Actor"])
f434b2f4-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-.-f434b2f4-04f9-11ee-9497-96a6d2455259_s(["Publication Event Role Type"])
8d23ca72-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-.-8d23ca72-424e-11ee-b0c4-00163e71351b_s(["Publication Event Place Appellation"])
d77d0958-424e-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-.-d77d0958-424e-11ee-b0c4-00163e71351b_s(["Publication Event Role Actor Appellation"])
f4349fc6-04f9-11ee-9497-96a6d2455259["frbr:F28_Expression_Creation"]-.-f4349fc6-04f9-11ee-9497-96a6d2455259_s(["Expression Creation"])
f434a6e2-04f9-11ee-9497-96a6d2455259["frbr:F30_Publication_Event"]-.-f434a6e2-04f9-11ee-9497-96a6d2455259_s(["Publication Event"])
b3d2c494-424d-11ee-974d-00163e71351b["crm:E41_Appellation"]-.-b3d2c494-424d-11ee-974d-00163e71351b_s(["Publication Event Actor Appellation"])
8e8e330e-4256-11ee-bc5c-00163e71351b["crm:E41_Appellation"]-.-8e8e330e-4256-11ee-bc5c-00163e71351b_s(["Expression Creation Actor Appellation"])
14d70cca-4256-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-.-14d70cca-4256-11ee-b0c4-00163e71351b_s(["Expression Creation Place Appellation"])
f434bcb8-04f9-11ee-9497-96a6d2455259["rdfs:Literal"]-.-f434bcb8-04f9-11ee-9497-96a6d2455259_s(["Expression Creation Time-Span Begin"])
f434be66-04f9-11ee-9497-96a6d2455259["rdfs:Literal"]-.-f434be66-04f9-11ee-9497-96a6d2455259_s(["Expression Creation Time-Span End"])
2bae605a-4257-11ee-b0c4-00163e71351b["crm:E41_Appellation"]-.-2bae605a-4257-11ee-b0c4-00163e71351b_s(["Expression Creation Role Actor Appellation"])
f434be16-04f9-11ee-9497-96a6d2455259["crm:E39_Actor"]-.-f434be16-04f9-11ee-9497-96a6d2455259_s(["Expression Creation Role Actor"])
f434bd8a-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-.-f434bd8a-04f9-11ee-9497-96a6d2455259_s(["Expression Creation Role Type"])
f434b0b0-04f9-11ee-9497-96a6d2455259["crm:E56_Language"]-.-f434b0b0-04f9-11ee-9497-96a6d2455259_s(["Expression Creation Linguistic Object Language"])
style 14d7106c-4256-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style 14d711ac-4256-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style 2bae65a0-4257-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style 2bae6758-4257-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style 8d23ce14-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style 8d23cf40-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style 8e8e36ce-4256-11ee-bc5c-00163e71351b_s stroke-dasharray: 5
style 8e8e3818-4256-11ee-bc5c-00163e71351b_s stroke-dasharray: 5
style b3d2ccbe-424d-11ee-974d-00163e71351b_s stroke-dasharray: 5
style b3d2cf84-424d-11ee-974d-00163e71351b_s stroke-dasharray: 5
style d77d0d22-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style d77d0e58-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style f434beac-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434bb0a-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434bbe6-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434bdd0-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434bb50-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434cec4-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b060-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434bac4-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434cf0a-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434affc-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b57e-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b2ae-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b538-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b5c4-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b2f4-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style 8d23ca72-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style d77d0958-424e-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style f4349fc6-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434a6e2-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style b3d2c494-424d-11ee-974d-00163e71351b_s stroke-dasharray: 5
style 8e8e330e-4256-11ee-bc5c-00163e71351b_s stroke-dasharray: 5
style 14d70cca-4256-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style f434bcb8-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434be66-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style 2bae605a-4257-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style f434be16-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434bd8a-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b0b0-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style 14d70cca-4256-11ee-b0c4-00163e71351b fill:#EEE8AA
style 14d7106c-4256-11ee-b0c4-00163e71351b fill:#D3D3D3
style 14d711ac-4256-11ee-b0c4-00163e71351b fill:#ffa500
style 14d712a6-4256-11ee-b0c4-00163e71351b fill:#D3D3D3
style 2bae605a-4257-11ee-b0c4-00163e71351b fill:#EEE8AA
style 2bae65a0-4257-11ee-b0c4-00163e71351b fill:#D3D3D3
style 2bae6758-4257-11ee-b0c4-00163e71351b fill:#ffa500
style 2bae68d4-4257-11ee-b0c4-00163e71351b fill:#D3D3D3
style 8d23ca72-424e-11ee-b0c4-00163e71351b fill:#EEE8AA
style 8d23ce14-424e-11ee-b0c4-00163e71351b fill:#D3D3D3
style 8d23cf40-424e-11ee-b0c4-00163e71351b fill:#ffa500
style 8d23d03a-424e-11ee-b0c4-00163e71351b fill:#D3D3D3
style 8e8e330e-4256-11ee-bc5c-00163e71351b fill:#EEE8AA
style 8e8e36ce-4256-11ee-bc5c-00163e71351b fill:#D3D3D3
style 8e8e3818-4256-11ee-bc5c-00163e71351b fill:#ffa500
style 8e8e3908-4256-11ee-bc5c-00163e71351b fill:#D3D3D3
style b3d2c494-424d-11ee-974d-00163e71351b fill:#EEE8AA
style b3d2ccbe-424d-11ee-974d-00163e71351b fill:#D3D3D3
style b3d2cf84-424d-11ee-974d-00163e71351b fill:#ffa500
style b3d2d1dc-424d-11ee-974d-00163e71351b fill:#D3D3D3
style d77d0958-424e-11ee-b0c4-00163e71351b fill:#EEE8AA
style d77d0d22-424e-11ee-b0c4-00163e71351b fill:#D3D3D3
style d77d0e58-424e-11ee-b0c4-00163e71351b fill:#ffa500
style d77d0f5c-424e-11ee-b0c4-00163e71351b fill:#D3D3D3
style f4349fc6-04f9-11ee-9497-96a6d2455259 fill:#5DAEEC
style f434a6e2-04f9-11ee-9497-96a6d2455259 fill:#5DAEEC
style f434affc-04f9-11ee-9497-96a6d2455259 fill:#76A5AF
style f434b060-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434b0b0-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434b2ae-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434b2f4-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434b538-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434b57e-04f9-11ee-9497-96a6d2455259 fill:#8CBF76
style f434b5c4-04f9-11ee-9497-96a6d2455259 fill:#ffc0cb
style f434b68c-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434ba38-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434bac4-04f9-11ee-9497-96a6d2455259 fill:#ffc0cb
style f434bb0a-04f9-11ee-9497-96a6d2455259 fill:#ffc0cb
style f434bb50-04f9-11ee-9497-96a6d2455259 fill:#8CBF76
style f434bba0-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434bbe6-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434bc22-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434bc72-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434bcb8-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434bcfe-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434bd44-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434bd8a-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434bdd0-04f9-11ee-9497-96a6d2455259 fill:#76A5AF
style f434be16-04f9-11ee-9497-96a6d2455259 fill:#ffc0cb
style f434be66-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434beac-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434c514-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434c55a-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434cec4-04f9-11ee-9497-96a6d2455259 fill:#ffff00
style f434cf0a-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434d216-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style fe246a5e-4bc4-11ee-b0c4-00163e71351b fill:#D3D3D3
```
