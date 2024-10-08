```mermaid
graph LR
style 24a98d4a-522c-11ee-bc5c-00163e71351b fill:#5DAEEC
style 3e873424-522c-11ee-974d-00163e71351b fill:#ffc0cb
style 4d27c45e-522b-11ee-974d-00163e71351b fill:#ffa500
style 58e05d5a-522c-11ee-a9ac-00163e71351b fill:#76A5AF
style 62491f63-dc8a-11ee-8bff-960002548b4f fill:#D3D3D3
24a98d4a-522c-11ee-bc5c-00163e71351b["crmE83_Type_Creation"]-->|"crm:P14_carried_out_by"|3e873424-522c-11ee-974d-00163e71351b["crm:E74_Group"]
24a98d4a-522c-11ee-bc5c-00163e71351b["crmE83_Type_Creation"]-->|"crm:P4_has_time-span"|58e05d5a-522c-11ee-a9ac-00163e71351b["crm:E52_Time-Span"]
4d27c45e-522b-11ee-974d-00163e71351b["crm:E99_Product_Type"]-->|"crm:P94i_was_created_by"|24a98d4a-522c-11ee-bc5c-00163e71351b["crmE83_Type_Creation"]
58e05d5a-522c-11ee-a9ac-00163e71351b["crm:E52_Time-Span"]-->|"crm:P170i_time_is_defined_by"|62491f63-dc8a-11ee-8bff-960002548b4f["crm:E61_Time_Primitive"]
style 3e873424-522c-11ee-974d-00163e71351b_s stroke-dasharray: 5
style 58e05d5a-522c-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 24a98d4a-522c-11ee-bc5c-00163e71351b_s stroke-dasharray: 5
style 62491f63-dc8a-11ee-8bff-960002548b4f_s stroke-dasharray: 5
3e873424-522c-11ee-974d-00163e71351b["crm:E74_Group"]-.-3e873424-522c-11ee-974d-00163e71351b_s(["Creatie ontwerper"])
58e05d5a-522c-11ee-a9ac-00163e71351b["crm:E52_Time-Span"]-.-58e05d5a-522c-11ee-a9ac-00163e71351b_s(["Type Creation Time-Span"])
24a98d4a-522c-11ee-bc5c-00163e71351b["crmE83_Type_Creation"]-.-24a98d4a-522c-11ee-bc5c-00163e71351b_s(["Type Creation"])
62491f63-dc8a-11ee-8bff-960002548b4f["crm:E61_Time_Primitive"]-.-62491f63-dc8a-11ee-8bff-960002548b4f_s(["Creatie datering"])
```
