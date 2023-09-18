```mermaid
graph LR
3dd7317e-b4e3-11ec-9349-9cf387da2c40["crm:E41_Appellation"]-->|"crm:P3_has_note"|52db2ac6-b4e3-11ec-9349-9cf387da2c40(rdfs:Literal)
1dcf1ebe-b4e3-11ec-9349-9cf387da2c40["crm:E41_Appellation"]-.-1dcf1ebe-b4e3-11ec-9349-9cf387da2c40_s(["ID"])
6da8f02c-b4e3-11ec-9349-9cf387da2c40["crm:E55_Type"]-.-6da8f02c-b4e3-11ec-9349-9cf387da2c40_s(["Inschrijvingsnummer type"])
52db2ac6-b4e3-11ec-9349-9cf387da2c40["rdfs:Literal"]-.-52db2ac6-b4e3-11ec-9349-9cf387da2c40_s(["Inschrijvingsnummer"])
d1dd8b50-a5fe-11ec-b19f-9cf387da2c40["crm:E41_Appellation"]-.-d1dd8b50-a5fe-11ec-b19f-9cf387da2c40_s(["ID"])
style 1dcf1ebe-b4e3-11ec-9349-9cf387da2c40_s stroke-dasharray: 5
style 6da8f02c-b4e3-11ec-9349-9cf387da2c40_s stroke-dasharray: 5
style 52db2ac6-b4e3-11ec-9349-9cf387da2c40_s stroke-dasharray: 5
style d1dd8b50-a5fe-11ec-b19f-9cf387da2c40_s stroke-dasharray: 5
076d1fc2-b4e3-11ec-9349-9cf387da2c40["crm:E8_Acquisition"]-->|"crm:P1_is_identified_by"|1dcf1ebe-b4e3-11ec-9349-9cf387da2c40["crm:E41_Appellation"]
3dd7317e-b4e3-11ec-9349-9cf387da2c40["crm:E41_Appellation"]-->|"crm:P2_has_type"|6da8f02c-b4e3-11ec-9349-9cf387da2c40["crm:E55_Type"]
cb619fd0-b4e2-11ec-9349-9cf387da2c40["crm:E7_Activity"]-->|"crm:P1_is_identified_by"|3dd7317e-b4e3-11ec-9349-9cf387da2c40["crm:E41_Appellation"]
cb619fd0-b4e2-11ec-9349-9cf387da2c40["crm:E7_Activity"]-->|"crm:P9i_forms_part_of"|076d1fc2-b4e3-11ec-9349-9cf387da2c40["crm:E8_Acquisition"]
d1dc46aa-a5fe-11ec-b19f-9cf387da2c40["crm:E78_Curated_Holding"]-->|"crm:P1_is_identified_by"|d1dd8b50-a5fe-11ec-b19f-9cf387da2c40["crm:E41_Appellation"]
d1dd96e0-a5fe-11ec-b19f-9cf387da2c40["crm:E22_Man-Made_Object"]-->|"crm:P12i_was_present_at"|cb619fd0-b4e2-11ec-9349-9cf387da2c40["crm:E7_Activity"]
d1dd96e0-a5fe-11ec-b19f-9cf387da2c40["crm:E22_Man-Made_Object"]-->|"crm:P46i_forms_part_of"|d1dc46aa-a5fe-11ec-b19f-9cf387da2c40["crm:E78_Curated_Holding"]
style 076d1fc2-b4e3-11ec-9349-9cf387da2c40 fill:#5DAEEC
style 1dcf1ebe-b4e3-11ec-9349-9cf387da2c40 fill:#EEE8AA
style 3dd7317e-b4e3-11ec-9349-9cf387da2c40 fill:#EEE8AA
style 52db2ac6-b4e3-11ec-9349-9cf387da2c40 fill:#D3D3D3
style 6da8f02c-b4e3-11ec-9349-9cf387da2c40 fill:#ffa500
style cb619fd0-b4e2-11ec-9349-9cf387da2c40 fill:#5DAEEC
style d1dc46aa-a5fe-11ec-b19f-9cf387da2c40 fill:#B0927A
style d1dd8b50-a5fe-11ec-b19f-9cf387da2c40 fill:#EEE8AA
```