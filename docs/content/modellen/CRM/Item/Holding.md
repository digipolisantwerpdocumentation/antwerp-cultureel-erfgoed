```mermaid
graph LR
3ba3010e-472b-11ee-974d-00163e71351b["rdfs:Literal"]-.-3ba3010e-472b-11ee-974d-00163e71351b_s(["Standplaats"])
5b5c4a00-472b-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]-.-5b5c4a00-472b-11ee-a9ac-00163e71351b_s(["Producttype"])
307b2270-472b-11ee-a9ac-00163e71351b["crm:E39_Actor"]-.-307b2270-472b-11ee-a9ac-00163e71351b_s(["Eigenaar"])
307b2270-472b-11ee-a9ac-00163e71351b["crm:E39_Actor"]-->|"rdfs:label"|307b2a18-472b-11ee-a9ac-00163e71351b(xsd:string)
3ba2ef70-472b-11ee-974d-00163e71351b["crm:E53_Place"]-->|"crm:P3_has_note"|3ba2f90c-472b-11ee-974d-00163e71351b(rdfs:Literal)
3ba2f240-472b-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P190_has_symbolic_content"|3ba3010e-472b-11ee-974d-00163e71351b(rdfs:Literal)
3ba2fe66-472b-11ee-974d-00163e71351b["crm:E56_Language"]-->|"rdfs:label"|3ba2fd80-472b-11ee-974d-00163e71351b(xsd:string)
style 307b2270-472b-11ee-a9ac-00163e71351b fill:#ffc0cb
style 307b2a18-472b-11ee-a9ac-00163e71351b fill:#D3D3D3
style 3ba2ef70-472b-11ee-974d-00163e71351b fill:#8CBF76
style 3ba2f240-472b-11ee-974d-00163e71351b fill:#ffff00
style 3ba2f90c-472b-11ee-974d-00163e71351b fill:#D3D3D3
style 3ba2fd80-472b-11ee-974d-00163e71351b fill:#D3D3D3
style 3ba2fe66-472b-11ee-974d-00163e71351b fill:#ffa500
style 3ba3010e-472b-11ee-974d-00163e71351b fill:#D3D3D3
style 5b5c4a00-472b-11ee-a9ac-00163e71351b fill:#ffff00
style 3ba3010e-472b-11ee-974d-00163e71351b_s stroke-dasharray: 5
style 5b5c4a00-472b-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 307b2270-472b-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
3ba2ef70-472b-11ee-974d-00163e71351b["crm:E53_Place"]-->|"crm:P1_is_identified_by"|3ba2f240-472b-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]
3ba2f240-472b-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P72_has_language"|3ba2fe66-472b-11ee-974d-00163e71351b["crm:E56_Language"]
9503f17e-4729-11ee-974d-00163e71351b["crm:E22_Man-Made_Object"]-->|"crm:P137_exemplifies"|5b5c4a00-472b-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]
9503f17e-4729-11ee-974d-00163e71351b["crm:E22_Man-Made_Object"]-->|"crm:P52_has_current_owner"|307b2270-472b-11ee-a9ac-00163e71351b["crm:E39_Actor"]
9503f17e-4729-11ee-974d-00163e71351b["crm:E22_Man-Made_Object"]-->|"crm:P55_has_current_location"|3ba2ef70-472b-11ee-974d-00163e71351b["crm:E53_Place"]
```
