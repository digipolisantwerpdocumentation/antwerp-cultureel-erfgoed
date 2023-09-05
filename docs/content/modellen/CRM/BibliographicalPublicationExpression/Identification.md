```mermaid
graph LR
f434906c-04f9-11ee-9497-96a6d2455259["crm:E35_Title"]-->|"crm:P2_has_type"|f434b1dc-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]
f434906c-04f9-11ee-9497-96a6d2455259["crm:E35_Title"]-->|"crm:P72_has_language"|f434b100-04f9-11ee-9497-96a6d2455259["crm:E56_Language"]
f43493fa-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"crm:P2_has_type"|f434b344-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]
f43495b2-04f9-11ee-9497-96a6d2455259["crm:E42_Identifier"]-->|"crm:P2_has_type"|f434b4ac-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]
f4349760-04f9-11ee-9497-96a6d2455259["frbr:F1_Work"]-->|"crm:P1_is_identified_by"|f434b722-04f9-11ee-9497-96a6d2455259["crm:E42_Identifier"]
f4349ac6-04f9-11ee-9497-96a6d2455259["crm:E36_Visual_Item"]-->|"la:digitally_carried_by"|f434b6dc-04f9-11ee-9497-96a6d2455259["crmdig:D1_Digital_Object"]
f434b650-04f9-11ee-9497-96a6d2455259["frbr:F24_Publication_Expression"]-->|"frbr:R3i_realises"|f4349760-04f9-11ee-9497-96a6d2455259["frbr:F1_Work"]
f434b650-04f9-11ee-9497-96a6d2455259["frbr:F24_Publication_Expression"]-->|"crm:P1_is_identified_by"|f43495b2-04f9-11ee-9497-96a6d2455259["crm:E42_Identifier"]
f434b650-04f9-11ee-9497-96a6d2455259["frbr:F24_Publication_Expression"]-->|"crm:P102_has_title"|f434906c-04f9-11ee-9497-96a6d2455259["crm:E35_Title"]
f434b650-04f9-11ee-9497-96a6d2455259["frbr:F24_Publication_Expression"]-->|"crm:P128i_is_carried_by"|f4349242-04f9-11ee-9497-96a6d2455259["crm:E22_Man-Made_Object"]
f434b650-04f9-11ee-9497-96a6d2455259["frbr:F24_Publication_Expression"]-->|"crm:P138i_has_representation"|f4349ac6-04f9-11ee-9497-96a6d2455259["crm:E36_Visual_Item"]
f434b650-04f9-11ee-9497-96a6d2455259["frbr:F24_Publication_Expression"]-->|"crm:P2_has_type"|f43493fa-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]
f434b722-04f9-11ee-9497-96a6d2455259["crm:E42_Identifier"]-->|"crm:P2_has_type"|f434c050-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]
f434906c-04f9-11ee-9497-96a6d2455259["crm:E35_Title"]-->|"crm:P190_has_symbolic_content"|f434b222-04f9-11ee-9497-96a6d2455259(rdfs:Literal)
f43493fa-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"rdfs:label"|f434b3d0-04f9-11ee-9497-96a6d2455259(xsd:string)
f43495b2-04f9-11ee-9497-96a6d2455259["crm:E42_Identifier"]-->|"crm:P190_has_symbolic_content"|f434b466-04f9-11ee-9497-96a6d2455259(rdfs:Literal)
f434b100-04f9-11ee-9497-96a6d2455259["crm:E56_Language"]-->|"rdfs:label"|f434b268-04f9-11ee-9497-96a6d2455259(xsd:string)
f434b1dc-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"rdfs:label"|f434b146-04f9-11ee-9497-96a6d2455259(xsd:string)
f434b344-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"rdfs:label"|f434b38a-04f9-11ee-9497-96a6d2455259(xsd:string)
f434b4ac-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"rdfs:label"|f434b4f2-04f9-11ee-9497-96a6d2455259(xsd:string)
f434b722-04f9-11ee-9497-96a6d2455259["crm:E42_Identifier"]-->|"crm:P190_has_symbolic_content"|f434ba7e-04f9-11ee-9497-96a6d2455259(rdfs:Literal)
f434c050-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"rdfs:label"|f434ca0a-04f9-11ee-9497-96a6d2455259(xsd:string)
f434b222-04f9-11ee-9497-96a6d2455259["rdfs:Literal"]-.-f434b222-04f9-11ee-9497-96a6d2455259_s(["Title Content"])
f434b1dc-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-.-f434b1dc-04f9-11ee-9497-96a6d2455259_s(["Title Type"])
f434b100-04f9-11ee-9497-96a6d2455259["crm:E56_Language"]-.-f434b100-04f9-11ee-9497-96a6d2455259_s(["Title Language"])
f434b344-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-.-f434b344-04f9-11ee-9497-96a6d2455259_s(["Type Type"])
f434b466-04f9-11ee-9497-96a6d2455259["rdfs:Literal"]-.-f434b466-04f9-11ee-9497-96a6d2455259_s(["Identifier Content"])
f434b4ac-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-.-f434b4ac-04f9-11ee-9497-96a6d2455259_s(["Identifier Type"])
f434b722-04f9-11ee-9497-96a6d2455259["crm:E42_Identifier"]-.-f434b722-04f9-11ee-9497-96a6d2455259_s(["Work Identifier"])
f434b6dc-04f9-11ee-9497-96a6d2455259["crmdig:D1_Digital_Object"]-.-f434b6dc-04f9-11ee-9497-96a6d2455259_s(["Digital Object"])
f4349760-04f9-11ee-9497-96a6d2455259["frbr:F1_Work"]-.-f4349760-04f9-11ee-9497-96a6d2455259_s(["Work"])
f43495b2-04f9-11ee-9497-96a6d2455259["crm:E42_Identifier"]-.-f43495b2-04f9-11ee-9497-96a6d2455259_s(["Identifier"])
f434906c-04f9-11ee-9497-96a6d2455259["crm:E35_Title"]-.-f434906c-04f9-11ee-9497-96a6d2455259_s(["Title"])
f4349242-04f9-11ee-9497-96a6d2455259["crm:E22_Man-Made_Object"]-.-f4349242-04f9-11ee-9497-96a6d2455259_s(["Bibliograpic Item"])
f4349ac6-04f9-11ee-9497-96a6d2455259["crm:E36_Visual_Item"]-.-f4349ac6-04f9-11ee-9497-96a6d2455259_s(["Visual Item"])
f43493fa-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-.-f43493fa-04f9-11ee-9497-96a6d2455259_s(["Type"])
f434ba7e-04f9-11ee-9497-96a6d2455259["rdfs:Literal"]-.-f434ba7e-04f9-11ee-9497-96a6d2455259_s(["Work Identifier Content"])
f434c050-04f9-11ee-9497-96a6d2455259["crm:E55_Type"]-.-f434c050-04f9-11ee-9497-96a6d2455259_s(["Work Identifier Type"])
style f434b222-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b1dc-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b100-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b344-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b466-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b4ac-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b722-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434b6dc-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f4349760-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f43495b2-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434906c-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f4349242-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f4349ac6-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f43493fa-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434ba7e-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434c050-04f9-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style f434906c-04f9-11ee-9497-96a6d2455259 fill:#EEE8AA
style f4349242-04f9-11ee-9497-96a6d2455259 fill:#B0927A
style f43493fa-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f43495b2-04f9-11ee-9497-96a6d2455259 fill:#EEE8AA
style f4349760-04f9-11ee-9497-96a6d2455259 fill:#ffff00
style f4349ac6-04f9-11ee-9497-96a6d2455259 fill:#ffff00
style f434b100-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434b146-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434b1dc-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434b222-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434b268-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434b344-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434b38a-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434b3d0-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434b466-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434b4ac-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434b4f2-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434b6dc-04f9-11ee-9497-96a6d2455259 fill:#C5B4E3
style f434b722-04f9-11ee-9497-96a6d2455259 fill:#EEE8AA
style f434ba7e-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
style f434c050-04f9-11ee-9497-96a6d2455259 fill:#ffa500
style f434ca0a-04f9-11ee-9497-96a6d2455259 fill:#D3D3D3
```
