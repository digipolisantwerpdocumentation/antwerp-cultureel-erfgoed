```mermaid
graph LR
5989fdd8-ee3b-11ed-9655-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P2_has_type"|598a0170-ee3b-11ed-9655-00163e71351b["crm:E55_Type"]
5989fdd8-ee3b-11ed-9655-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P72_has_language"|598a0292-ee3b-11ed-9655-00163e71351b["crm:E56_Language"]
652f5150-eda1-11ed-9064-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P2_has_type"|652f5a42-eda1-11ed-9064-00163e71351b["crm:E55_Type"]
652f5150-eda1-11ed-9064-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P72_has_language"|652f5d62-eda1-11ed-9064-00163e71351b["crm:E56_Language"]
fa95cea2-dd27-11ed-9655-00163e71351b["crm:E22_Man-Made_Object"]-->|"crm:P129i_is_subject_of"|652f5150-eda1-11ed-9064-00163e71351b["crm:E33_Linguistic_Object"]
fa95cea2-dd27-11ed-9655-00163e71351b["crm:E22_Man-Made_Object"]-->|"crm:P67i_is_referred_to_by"|5989fdd8-ee3b-11ed-9655-00163e71351b["crm:E33_Linguistic_Object"]
5989fdd8-ee3b-11ed-9655-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P190_has_symbolic_content"|598a0382-ee3b-11ed-9655-00163e71351b(rdfs:Literal)
598a0170-ee3b-11ed-9655-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|598a054e-ee3b-11ed-9655-00163e71351b(xsd:string)
598a0292-ee3b-11ed-9655-00163e71351b["crm:E56_Language"]-->|"rdfs:label"|598a0468-ee3b-11ed-9655-00163e71351b(xsd:string)
652f5150-eda1-11ed-9064-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P190_has_symbolic_content"|652f56d2-eda1-11ed-9064-00163e71351b(rdfs:Literal)
652f5a42-eda1-11ed-9064-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|652f58a8-eda1-11ed-9064-00163e71351b(xsd:string)
652f5d62-eda1-11ed-9064-00163e71351b["crm:E56_Language"]-->|"rdfs:label"|652f5bc8-eda1-11ed-9064-00163e71351b(xsd:string)
fa95cea2-dd27-11ed-9655-00163e71351b["crm:E22_Man-Made_Object"]-->|"crm:P3_has_note"|f9afbb9e-eda1-11ed-9232-00163e71351b(rdfs:Literal)
598a0382-ee3b-11ed-9655-00163e71351b["rdfs:Literal"]-.-598a0382-ee3b-11ed-9655-00163e71351b_s(["Annotation Content"])
598a0170-ee3b-11ed-9655-00163e71351b["crm:E55_Type"]-.-598a0170-ee3b-11ed-9655-00163e71351b_s(["Annotation Type"])
598a0292-ee3b-11ed-9655-00163e71351b["crm:E56_Language"]-.-598a0292-ee3b-11ed-9655-00163e71351b_s(["Annotation Language"])
652f56d2-eda1-11ed-9064-00163e71351b["rdfs:Literal"]-.-652f56d2-eda1-11ed-9064-00163e71351b_s(["Description Content"])
652f5a42-eda1-11ed-9064-00163e71351b["crm:E55_Type"]-.-652f5a42-eda1-11ed-9064-00163e71351b_s(["Description Type"])
652f5d62-eda1-11ed-9064-00163e71351b["crm:E56_Language"]-.-652f5d62-eda1-11ed-9064-00163e71351b_s(["Description Language"])
652f5150-eda1-11ed-9064-00163e71351b["crm:E33_Linguistic_Object"]-.-652f5150-eda1-11ed-9064-00163e71351b_s(["Description"])
f9afbb9e-eda1-11ed-9232-00163e71351b["rdfs:Literal"]-.-f9afbb9e-eda1-11ed-9232-00163e71351b_s(["Note"])
5989fdd8-ee3b-11ed-9655-00163e71351b["crm:E33_Linguistic_Object"]-.-5989fdd8-ee3b-11ed-9655-00163e71351b_s(["Annotation"])
style 598a0382-ee3b-11ed-9655-00163e71351b_s stroke-dasharray: 5
style 598a0170-ee3b-11ed-9655-00163e71351b_s stroke-dasharray: 5
style 598a0292-ee3b-11ed-9655-00163e71351b_s stroke-dasharray: 5
style 652f56d2-eda1-11ed-9064-00163e71351b_s stroke-dasharray: 5
style 652f5a42-eda1-11ed-9064-00163e71351b_s stroke-dasharray: 5
style 652f5d62-eda1-11ed-9064-00163e71351b_s stroke-dasharray: 5
style 652f5150-eda1-11ed-9064-00163e71351b_s stroke-dasharray: 5
style f9afbb9e-eda1-11ed-9232-00163e71351b_s stroke-dasharray: 5
style 5989fdd8-ee3b-11ed-9655-00163e71351b_s stroke-dasharray: 5
style 5989fdd8-ee3b-11ed-9655-00163e71351b fill:#ffff00
style 598a0170-ee3b-11ed-9655-00163e71351b fill:#ffa500
style 598a0292-ee3b-11ed-9655-00163e71351b fill:#ffa500
style 598a0382-ee3b-11ed-9655-00163e71351b fill:#D3D3D3
style 598a0468-ee3b-11ed-9655-00163e71351b fill:#D3D3D3
style 598a054e-ee3b-11ed-9655-00163e71351b fill:#D3D3D3
style 652f5150-eda1-11ed-9064-00163e71351b fill:#ffff00
style 652f56d2-eda1-11ed-9064-00163e71351b fill:#D3D3D3
style 652f58a8-eda1-11ed-9064-00163e71351b fill:#D3D3D3
style 652f5a42-eda1-11ed-9064-00163e71351b fill:#ffa500
style 652f5bc8-eda1-11ed-9064-00163e71351b fill:#D3D3D3
style 652f5d62-eda1-11ed-9064-00163e71351b fill:#ffa500
style f9afbb9e-eda1-11ed-9232-00163e71351b fill:#D3D3D3
```
