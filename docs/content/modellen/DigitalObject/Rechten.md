```mermaid
graph LR
ad7fab56-04fa-11ee-9497-96a6d2455259["crm:E30_Right"]-->|"crm:P3_has_note"|ad7fc7b2-04fa-11ee-9497-96a6d2455259(rdfs:Literal)
ad7faeda-04fa-11ee-9497-96a6d2455259["crm:E56_Language"]-->|"rdfs:label"|ad7fc28a-04fa-11ee-9497-96a6d2455259(xsd:string)
ad7fbe3e-04fa-11ee-9497-96a6d2455259["crm:E55_Type"]-->|"rdfs:label"|ad7fc05a-04fa-11ee-9497-96a6d2455259(xsd:string)
ad7fc398-04fa-11ee-9497-96a6d2455259["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P190_has_symbolic_content"|ad7fc49c-04fa-11ee-9497-96a6d2455259(rdfs:Literal)
ad7fc5a0-04fa-11ee-9497-96a6d2455259["crm:E56_Language"]-->|"rdfs:label"|ad7fc6a4-04fa-11ee-9497-96a6d2455259(xsd:string)
ad7fc8ac-04fa-11ee-9497-96a6d2455259["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P190_has_symbolic_content"|ad7fbf56-04fa-11ee-9497-96a6d2455259(rdfs:Literal)
ad7fab56-04fa-11ee-9497-96a6d2455259["crm:E30_Right"]-->|"crm:P1_is_identified_by"|ad7fc398-04fa-11ee-9497-96a6d2455259["crm:E33_E41_Linguistic_Appellation"]
ad7fab56-04fa-11ee-9497-96a6d2455259["crm:E30_Right"]-->|"crm:P75i_is_possessed_by"|ad7fc17c-04fa-11ee-9497-96a6d2455259["crm:E39_Actor"]
ad7fb3a8-04fa-11ee-9497-96a6d2455259["crmdig:D1_Digital_Object"]-->|"crm:P104_is_subject_to"|ad7fab56-04fa-11ee-9497-96a6d2455259["crm:E30_Right"]
ad7fc17c-04fa-11ee-9497-96a6d2455259["crm:E39_Actor"]-->|"crm:P1_is_identified_by"|ad7fc8ac-04fa-11ee-9497-96a6d2455259["crm:E33_E41_Linguistic_Appellation"]
ad7fc398-04fa-11ee-9497-96a6d2455259["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P72_has_language"|ad7fc5a0-04fa-11ee-9497-96a6d2455259["crm:E56_Language"]
ad7fc8ac-04fa-11ee-9497-96a6d2455259["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P2_has_type"|ad7fbe3e-04fa-11ee-9497-96a6d2455259["crm:E55_Type"]
ad7fc8ac-04fa-11ee-9497-96a6d2455259["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P72_has_language"|ad7faeda-04fa-11ee-9497-96a6d2455259["crm:E56_Language"]
style ad7fc398-04fa-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style ad7fc7b2-04fa-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style ad7fc17c-04fa-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style ad7fab56-04fa-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style ad7fc8ac-04fa-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style ad7fc49c-04fa-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style ad7fc5a0-04fa-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style ad7fbf56-04fa-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style ad7fbe3e-04fa-11ee-9497-96a6d2455259_s stroke-dasharray: 5
style ad7faeda-04fa-11ee-9497-96a6d2455259_s stroke-dasharray: 5
ad7fc398-04fa-11ee-9497-96a6d2455259["crm:E33_E41_Linguistic_Appellation"]-.-ad7fc398-04fa-11ee-9497-96a6d2455259_s(["Recht naam"])
ad7fc7b2-04fa-11ee-9497-96a6d2455259["rdfs:Literal"]-.-ad7fc7b2-04fa-11ee-9497-96a6d2455259_s(["Recht opmerking"])
ad7fc17c-04fa-11ee-9497-96a6d2455259["crm:E39_Actor"]-.-ad7fc17c-04fa-11ee-9497-96a6d2455259_s(["Rechtenhouder"])
ad7fab56-04fa-11ee-9497-96a6d2455259["crm:E30_Right"]-.-ad7fab56-04fa-11ee-9497-96a6d2455259_s(["Recht"])
ad7fc8ac-04fa-11ee-9497-96a6d2455259["crm:E33_E41_Linguistic_Appellation"]-.-ad7fc8ac-04fa-11ee-9497-96a6d2455259_s(["Rechtenhouder naam"])
ad7fc49c-04fa-11ee-9497-96a6d2455259["rdfs:Literal"]-.-ad7fc49c-04fa-11ee-9497-96a6d2455259_s(["Recht naam inhoud"])
ad7fc5a0-04fa-11ee-9497-96a6d2455259["crm:E56_Language"]-.-ad7fc5a0-04fa-11ee-9497-96a6d2455259_s(["Recht naam taal uri"])
ad7fbf56-04fa-11ee-9497-96a6d2455259["rdfs:Literal"]-.-ad7fbf56-04fa-11ee-9497-96a6d2455259_s(["Rechtenhouder naam inhoud"])
ad7fbe3e-04fa-11ee-9497-96a6d2455259["crm:E55_Type"]-.-ad7fbe3e-04fa-11ee-9497-96a6d2455259_s(["Rechtenhouder naam type uri"])
ad7faeda-04fa-11ee-9497-96a6d2455259["crm:E56_Language"]-.-ad7faeda-04fa-11ee-9497-96a6d2455259_s(["Rechtenhouder naam taal uri"])
style ad7fab56-04fa-11ee-9497-96a6d2455259 fill:#ffff00
style ad7faeda-04fa-11ee-9497-96a6d2455259 fill:#ffa500
style ad7fbe3e-04fa-11ee-9497-96a6d2455259 fill:#ffa500
style ad7fbf56-04fa-11ee-9497-96a6d2455259 fill:#D3D3D3
style ad7fc05a-04fa-11ee-9497-96a6d2455259 fill:#D3D3D3
style ad7fc17c-04fa-11ee-9497-96a6d2455259 fill:#ffc0cb
style ad7fc28a-04fa-11ee-9497-96a6d2455259 fill:#D3D3D3
style ad7fc398-04fa-11ee-9497-96a6d2455259 fill:#ffff00
style ad7fc49c-04fa-11ee-9497-96a6d2455259 fill:#D3D3D3
style ad7fc5a0-04fa-11ee-9497-96a6d2455259 fill:#ffa500
style ad7fc6a4-04fa-11ee-9497-96a6d2455259 fill:#D3D3D3
style ad7fc7b2-04fa-11ee-9497-96a6d2455259 fill:#D3D3D3
style ad7fc8ac-04fa-11ee-9497-96a6d2455259 fill:#ffff00
```
