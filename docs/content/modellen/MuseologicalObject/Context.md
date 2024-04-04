```mermaid
graph LR
e3f399f0-eda2-11ed-9655-00163e71351b["crm:E39_Actor"]-->|"rdfs:label"|e3f39d10-eda2-11ed-9655-00163e71351b(xsd:string)
fa955724-dd27-11ed-9655-00163e71351b["crm:E39_Actor"]-->|"rdfs:label"|fa95cf6a-dd27-11ed-9655-00163e71351b(xsd:string)
fa95cea2-dd27-11ed-9655-00163e71351b["crm:E22_Human-Made_Object"]-->|"crm:P50_has_current_keeper"|e3f399f0-eda2-11ed-9655-00163e71351b["crm:E39_Actor"]
fa95cea2-dd27-11ed-9655-00163e71351b["crm:E22_Human-Made_Object"]-->|"crm:P52_has_current_owner"|fa955724-dd27-11ed-9655-00163e71351b["crm:E39_Actor"]
e3f399f0-eda2-11ed-9655-00163e71351b["crm:E39_Actor"]-.-e3f399f0-eda2-11ed-9655-00163e71351b_s(["Huidige beheerder"])
fa955724-dd27-11ed-9655-00163e71351b["crm:E39_Actor"]-.-fa955724-dd27-11ed-9655-00163e71351b_s(["Huidige eigenaar"])
style e3f399f0-eda2-11ed-9655-00163e71351b_s stroke-dasharray: 5
style fa955724-dd27-11ed-9655-00163e71351b_s stroke-dasharray: 5
style e3f399f0-eda2-11ed-9655-00163e71351b fill:#ffc0cb
style e3f39d10-eda2-11ed-9655-00163e71351b fill:#D3D3D3
style fa955724-dd27-11ed-9655-00163e71351b fill:#ffc0cb
style fa95cea2-dd27-11ed-9655-00163e71351b fill:#B0927A
style fa95cf6a-dd27-11ed-9655-00163e71351b fill:#D3D3D3
```
