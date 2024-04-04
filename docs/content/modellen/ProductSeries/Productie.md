```mermaid
graph LR
03fa8dea-dc8b-11ee-997f-960002548b4f["crm:E52_Time-Span"]-->|"crm:P170i_time_is_defined_by"|2d3f4768-dc8b-11ee-ae3e-960002548b4f["crm:E61_Time_Primitive"]
4d27c45e-522b-11ee-974d-00163e71351b["crm:E99_Product_Type"]-->|"crm:P186i_is_produced_by"|90d070f6-dc8a-11ee-9063-960002548b4f["crm:E12_Production"]
90d070f6-dc8a-11ee-9063-960002548b4f["crm:E12_Production"]-->|"crm:P14_carried_out_by"|c93e0202-dc8a-11ee-ae5e-960002548b4f["crm:E74_Group"]
90d070f6-dc8a-11ee-9063-960002548b4f["crm:E12_Production"]-->|"crm:P4_has_time-span"|03fa8dea-dc8b-11ee-997f-960002548b4f["crm:E52_Time-Span"]
90d070f6-dc8a-11ee-9063-960002548b4f["crm:E12_Production"]-->|"crm:P7_took_place_at"|e21bd5db-dc8a-11ee-991e-960002548b4f["crm:E53_Place"]
2d3f4768-dc8b-11ee-ae3e-960002548b4f["crm:E61_Time_Primitive"]-.-2d3f4768-dc8b-11ee-ae3e-960002548b4f_s(["Productie datering"])
90d070f6-dc8a-11ee-9063-960002548b4f["crm:E12_Production"]-.-90d070f6-dc8a-11ee-9063-960002548b4f_s(["Production"])
c93e0202-dc8a-11ee-ae5e-960002548b4f["crm:E74_Group"]-.-c93e0202-dc8a-11ee-ae5e-960002548b4f_s(["Productie producent"])
03fa8dea-dc8b-11ee-997f-960002548b4f["crm:E52_Time-Span"]-.-03fa8dea-dc8b-11ee-997f-960002548b4f_s(["Production Time-Span"])
e21bd5db-dc8a-11ee-991e-960002548b4f["crm:E53_Place"]-.-e21bd5db-dc8a-11ee-991e-960002548b4f_s(["Productie productieplek"])
style 2d3f4768-dc8b-11ee-ae3e-960002548b4f_s stroke-dasharray: 5
style 90d070f6-dc8a-11ee-9063-960002548b4f_s stroke-dasharray: 5
style c93e0202-dc8a-11ee-ae5e-960002548b4f_s stroke-dasharray: 5
style 03fa8dea-dc8b-11ee-997f-960002548b4f_s stroke-dasharray: 5
style e21bd5db-dc8a-11ee-991e-960002548b4f_s stroke-dasharray: 5
style 03fa8dea-dc8b-11ee-997f-960002548b4f fill:#76A5AF
style 2d3f4768-dc8b-11ee-ae3e-960002548b4f fill:#D3D3D3
style 4d27c45e-522b-11ee-974d-00163e71351b fill:#ffa500
style 90d070f6-dc8a-11ee-9063-960002548b4f fill:#5DAEEC
style c93e0202-dc8a-11ee-ae5e-960002548b4f fill:#ffc0cb
style e21bd5db-dc8a-11ee-991e-960002548b4f fill:#8CBF76
```
