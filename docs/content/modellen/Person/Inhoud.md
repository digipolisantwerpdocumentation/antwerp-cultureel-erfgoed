```mermaid
graph LR
style 0d9d4cb4-e37c-11ed-9064-00163e71351b fill:#ffc0cb
style b9e8fff2-ed97-11ed-9655-00163e71351b fill:#ffff00
style b9e90498-ed97-11ed-9655-00163e71351b fill:#D3D3D3
style b9e907b8-ed97-11ed-9655-00163e71351b fill:#ffa500
style c5f20b3e-e439-11ed-a1e6-00163e71351b fill:#D3D3D3
0d9d4cb4-e37c-11ed-9064-00163e71351b["crm:E21_Person"]-->|"crm:P3_has_note"|c5f20b3e-e439-11ed-a1e6-00163e71351b(rdfs:Literal)
b9e8fff2-ed97-11ed-9655-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P190_has_symbolic_content"|b9e90498-ed97-11ed-9655-00163e71351b(rdfs:Literal)
0d9d4cb4-e37c-11ed-9064-00163e71351b["crm:E21_Person"]-->|"crm:P129i_is_subject_of"|b9e8fff2-ed97-11ed-9655-00163e71351b["crm:E33_Linguistic_Object"]
b9e8fff2-ed97-11ed-9655-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P2_has_type"|b9e907b8-ed97-11ed-9655-00163e71351b["crm:E55_Type"]
style c5f20b3e-e439-11ed-a1e6-00163e71351b_s stroke-dasharray: 5
style b9e90498-ed97-11ed-9655-00163e71351b_s stroke-dasharray: 5
style b9e907b8-ed97-11ed-9655-00163e71351b_s stroke-dasharray: 5
c5f20b3e-e439-11ed-a1e6-00163e71351b["rdfs:Literal"]-.-c5f20b3e-e439-11ed-a1e6-00163e71351b_s(["Opmerking"])
b9e90498-ed97-11ed-9655-00163e71351b["rdfs:Literal"]-.-b9e90498-ed97-11ed-9655-00163e71351b_s(["Beschrijving"])
b9e907b8-ed97-11ed-9655-00163e71351b["crm:E55_Type"]-.-b9e907b8-ed97-11ed-9655-00163e71351b_s(["aat:300435416 (beschrijving)"])
```
