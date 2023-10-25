```mermaid
graph LR
e3f399f0-eda2-11ed-9655-00163e71351b["crm:E39_Actor"]-->|"rdfs:label"|e3f39d10-eda2-11ed-9655-00163e71351b(xsd:string)
fa955724-dd27-11ed-9655-00163e71351b["crm:E39_Actor"]-->|"rdfs:label"|fa95cf6a-dd27-11ed-9655-00163e71351b(xsd:string)
fa95cea2-dd27-11ed-9655-00163e71351b["crm:E22_Man-Made_Object"]-->|"crm:P24i_changed_ownership_through"|2912c76c-62c5-11ee-b0c4-00163e71351b["crm:E8_Acquisition"]
fa95cea2-dd27-11ed-9655-00163e71351b["crm:E22_Man-Made_Object"]-->|"crm:P50_has_current_keeper"|e3f399f0-eda2-11ed-9655-00163e71351b["crm:E39_Actor"]
fa95cea2-dd27-11ed-9655-00163e71351b["crm:E22_Man-Made_Object"]-->|"crm:P52_has_current_owner"|fa955724-dd27-11ed-9655-00163e71351b["crm:E39_Actor"]
2912c76c-62c5-11ee-b0c4-00163e71351b["crm:E8_Acquisition"]-.-2912c76c-62c5-11ee-b0c4-00163e71351b_s(["Verwerving URI"])
e3f399f0-eda2-11ed-9655-00163e71351b["crm:E39_Actor"]-.-e3f399f0-eda2-11ed-9655-00163e71351b_s(["Huidige beheerder URI"])
fa955724-dd27-11ed-9655-00163e71351b["crm:E39_Actor"]-.-fa955724-dd27-11ed-9655-00163e71351b_s(["Huidige eigenaar URI"])
style 2912c76c-62c5-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style e3f399f0-eda2-11ed-9655-00163e71351b_s stroke-dasharray: 5
style fa955724-dd27-11ed-9655-00163e71351b_s stroke-dasharray: 5
style 2912c76c-62c5-11ee-b0c4-00163e71351b fill:#5DAEEC
style e3f399f0-eda2-11ed-9655-00163e71351b fill:#ffc0cb
style e3f39d10-eda2-11ed-9655-00163e71351b fill:#D3D3D3
style fa955724-dd27-11ed-9655-00163e71351b fill:#ffc0cb
style fa95cea2-dd27-11ed-9655-00163e71351b fill:#B0927A
style fa95cf6a-dd27-11ed-9655-00163e71351b fill:#D3D3D3
```
