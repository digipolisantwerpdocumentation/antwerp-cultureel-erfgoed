```mermaid
graph LR
style 1f0e84f8-e764-11ee-a1e0-960002548b4f fill:#D3D3D3
style 32ae71bf-dc8a-11ee-a0ec-960002548b4f fill:#ffff00
style 32ae78c0-dc8a-11ee-9eb4-960002548b4f fill:#D3D3D3
style 32ae7be7-dc8a-11ee-92ff-960002548b4f fill:#ffa500
style 32ae7d00-dc8a-11ee-b543-960002548b4f fill:#EEE8AA
style 4d27c45e-522b-11ee-974d-00163e71351b fill:#ffa500
32ae71bf-dc8a-11ee-a0ec-960002548b4f["crm:E33_Linguistic_Object"]-->|"crm:P190_has_symbolic_content"|32ae78c0-dc8a-11ee-9eb4-960002548b4f(rdfs:Literal)
32ae71bf-dc8a-11ee-a0ec-960002548b4f["crm:E33_Linguistic_Object"]-->|"crm:P72_has_language"|32ae7be7-dc8a-11ee-92ff-960002548b4f["crm:E56_Language"]
32ae7be7-dc8a-11ee-92ff-960002548b4f["crm:E56_Language"]-->|"crm:P1_is_identified_by"|32ae7d00-dc8a-11ee-b543-960002548b4f["crm:E41_Appellation"]
32ae7d00-dc8a-11ee-b543-960002548b4f["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|1f0e84f8-e764-11ee-a1e0-960002548b4f["crm:E62_String"]
4d27c45e-522b-11ee-974d-00163e71351b["crm:E99_Product_Type"]-->|"crm:P129i_is_subject_of"|32ae71bf-dc8a-11ee-a0ec-960002548b4f["crm:E33_Linguistic_Object"]
32ae78c0-dc8a-11ee-9eb4-960002548b4f["rdfs:Literal"]-.-32ae78c0-dc8a-11ee-9eb4-960002548b4f_s(["Beschrijving tekst"])
32ae7be7-dc8a-11ee-92ff-960002548b4f["crm:E56_Language"]-.-32ae7be7-dc8a-11ee-92ff-960002548b4f_s(["Description Language"])
32ae7d00-dc8a-11ee-b543-960002548b4f["crm:E41_Appellation"]-.-32ae7d00-dc8a-11ee-b543-960002548b4f_s(["Description Language Appellation"])
1f0e84f8-e764-11ee-a1e0-960002548b4f["crm:E62_String"]-.-1f0e84f8-e764-11ee-a1e0-960002548b4f_s(["Beschrijving taal"])
32ae71bf-dc8a-11ee-a0ec-960002548b4f["crm:E33_Linguistic_Object"]-.-32ae71bf-dc8a-11ee-a0ec-960002548b4f_s(["Description"])
style 32ae78c0-dc8a-11ee-9eb4-960002548b4f_s stroke-dasharray: 5
style 32ae7be7-dc8a-11ee-92ff-960002548b4f_s stroke-dasharray: 5
style 32ae7d00-dc8a-11ee-b543-960002548b4f_s stroke-dasharray: 5
style 1f0e84f8-e764-11ee-a1e0-960002548b4f_s stroke-dasharray: 5
style 32ae71bf-dc8a-11ee-a0ec-960002548b4f_s stroke-dasharray: 5
```
