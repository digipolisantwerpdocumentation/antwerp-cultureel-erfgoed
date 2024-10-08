```mermaid
graph LR
style bd7ef52c-eda1-11ed-9232-00163e71351b fill:#ffff00
style bd7ef9d2-eda1-11ed-9232-00163e71351b fill:#ffa500
style bd7efb6c-eda1-11ed-9232-00163e71351b fill:#D3D3D3
style bd7efe46-eda1-11ed-9232-00163e71351b fill:#ffc0cb
style bd7f00da-eda1-11ed-9232-00163e71351b fill:#ffff00
style bd7f0224-eda1-11ed-9232-00163e71351b fill:#D3D3D3
style bd7f05da-eda1-11ed-9232-00163e71351b fill:#D3D3D3
style bd7f071a-eda1-11ed-9232-00163e71351b fill:#EEE8AA
style fa95cea2-dd27-11ed-9655-00163e71351b fill:#B0927A
bd7ef52c-eda1-11ed-9232-00163e71351b["crm:E30_Right"]-->|"crm:P3_has_note"|bd7f05da-eda1-11ed-9232-00163e71351b(rdfs:Literal)
bd7f00da-eda1-11ed-9232-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P190_has_symbolic_content"|bd7f0224-eda1-11ed-9232-00163e71351b(rdfs:Literal)
bd7f071a-eda1-11ed-9232-00163e71351b["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|bd7efb6c-eda1-11ed-9232-00163e71351b(rdfs:Literal)
style bd7f05da-eda1-11ed-9232-00163e71351b_s stroke-dasharray: 5
style bd7efe46-eda1-11ed-9232-00163e71351b_s stroke-dasharray: 5
style bd7f0224-eda1-11ed-9232-00163e71351b_s stroke-dasharray: 5
style bd7efb6c-eda1-11ed-9232-00163e71351b_s stroke-dasharray: 5
style bd7ef9d2-eda1-11ed-9232-00163e71351b_s stroke-dasharray: 5
bd7ef52c-eda1-11ed-9232-00163e71351b["crm:E30_Right"]-->|"crm:P129i_is_subject_of"|bd7f00da-eda1-11ed-9232-00163e71351b["crm:E33_Linguistic_Object"]
bd7ef52c-eda1-11ed-9232-00163e71351b["crm:E30_Right"]-->|"crm:P75i_is_possessed_by"|bd7efe46-eda1-11ed-9232-00163e71351b["crm:E39_Actor"]
bd7efe46-eda1-11ed-9232-00163e71351b["crm:E39_Actor"]-->|"crm:P1_is_identified_by"|bd7f071a-eda1-11ed-9232-00163e71351b["crm:E41_Appellation"]
bd7f071a-eda1-11ed-9232-00163e71351b["crm:E41_Appellation"]-->|"crm:P2_has_type"|bd7ef9d2-eda1-11ed-9232-00163e71351b["crm:E55_Type"]
fa95cea2-dd27-11ed-9655-00163e71351b["crm:E22_Human-Made_Object"]-->|"crm:P104_is_subject_to"|bd7ef52c-eda1-11ed-9232-00163e71351b["crm:E30_Right"]
bd7f05da-eda1-11ed-9232-00163e71351b["rdfs:Literal"]-.-bd7f05da-eda1-11ed-9232-00163e71351b_s(["Recht opmerking"])
bd7efe46-eda1-11ed-9232-00163e71351b["crm:E39_Actor"]-.-bd7efe46-eda1-11ed-9232-00163e71351b_s(["Rechtenhouder"])
bd7f0224-eda1-11ed-9232-00163e71351b["rdfs:Literal"]-.-bd7f0224-eda1-11ed-9232-00163e71351b_s(["Recht beschrijving"])
bd7efb6c-eda1-11ed-9232-00163e71351b["rdfs:Literal"]-.-bd7efb6c-eda1-11ed-9232-00163e71351b_s(["Rechtenhouder naam"])
bd7ef9d2-eda1-11ed-9232-00163e71351b["crm:E55_Type"]-.-bd7ef9d2-eda1-11ed-9232-00163e71351b_s(["Rechtenhouder naam type"])
```
