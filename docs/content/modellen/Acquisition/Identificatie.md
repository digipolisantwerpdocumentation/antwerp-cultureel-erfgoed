```mermaid
graph LR
style 24843382-e542-11ee-8f1b-960002548b4f fill:#EEE8AA
style 35be857b-e542-11ee-98ef-960002548b4f fill:#D3D3D3
style 39e86e48-e994-11ed-9232-00163e71351b fill:#B0927A
style 7b658ca8-d44e-11ed-9064-00163e71351b fill:#5DAEEC
style b35a7c94-b086-11ee-b321-960002548b4f fill:#EEE8AA
style b35a81b6-b086-11ee-a40a-960002548b4f fill:#D3D3D3
style b35a82e2-b086-11ee-913f-960002548b4f fill:#ffa500
24843382-e542-11ee-8f1b-960002548b4f["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|35be857b-e542-11ee-98ef-960002548b4f(rdfs:Literal)
b35a7c94-b086-11ee-b321-960002548b4f["crm:E42_Identifier"]-->|"crm:P190_has_symbolic_content"|b35a81b6-b086-11ee-a40a-960002548b4f(rdfs:Literal)
7b658ca8-d44e-11ed-9064-00163e71351b["crm:E8_Acquisition"]-->|"crm:P1_is_identified_by"|24843382-e542-11ee-8f1b-960002548b4f["crm:E41_Appellation"]
7b658ca8-d44e-11ed-9064-00163e71351b["crm:E8_Acquisition"]-->|"crm:P1_is_identified_by"|b35a7c94-b086-11ee-b321-960002548b4f["crm:E42_Identifier"]
7b658ca8-d44e-11ed-9064-00163e71351b["crm:E8_Acquisition"]-->|"crm:P24_transferred_title_of"|39e86e48-e994-11ed-9232-00163e71351b["crm:E22_Human-Made_Object"]
b35a7c94-b086-11ee-b321-960002548b4f["crm:E42_Identifier"]-->|"crm:P2_has_type"|b35a82e2-b086-11ee-913f-960002548b4f["crm:E55_Type"]
35be857b-e542-11ee-98ef-960002548b4f["rdfs:Literal"]-.-35be857b-e542-11ee-98ef-960002548b4f_s(["Verwerving naam"])
39e86e48-e994-11ed-9232-00163e71351b["crm:E22_Human-Made_Object"]-.-39e86e48-e994-11ed-9232-00163e71351b_s(["Aangekocht object"])
b35a81b6-b086-11ee-a40a-960002548b4f["rdfs:Literal"]-.-b35a81b6-b086-11ee-a40a-960002548b4f_s(["Verwerving identificator"])
b35a82e2-b086-11ee-913f-960002548b4f["crm:E55_Type"]-.-b35a82e2-b086-11ee-913f-960002548b4f_s(["Verwerving identificator type"])
style 35be857b-e542-11ee-98ef-960002548b4f_s stroke-dasharray: 5
style 39e86e48-e994-11ed-9232-00163e71351b_s stroke-dasharray: 5
style b35a81b6-b086-11ee-a40a-960002548b4f_s stroke-dasharray: 5
style b35a82e2-b086-11ee-913f-960002548b4f_s stroke-dasharray: 5
```
