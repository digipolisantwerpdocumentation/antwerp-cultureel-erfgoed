```mermaid
graph LR
38940d7e-471b-11ee-a9ac-00163e71351b["crm:E12_Production"]-->|"crm:P126_employed"|51056852-4726-11ee-974d-00163e71351b["crm:E57_Material"]
38940d7e-471b-11ee-a9ac-00163e71351b["crm:E12_Production"]-->|"crm:P14_carried_out_by"|38941328-471b-11ee-a9ac-00163e71351b["crm:E39_Actor"]
38940d7e-471b-11ee-a9ac-00163e71351b["crm:E12_Production"]-->|"crm:P32_used_general_technique"|3894194a-471b-11ee-a9ac-00163e71351b["crm:E55_Type"]
38940d7e-471b-11ee-a9ac-00163e71351b["crm:E12_Production"]-->|"crm:P4_has_time-span"|389410f8-471b-11ee-a9ac-00163e71351b["crm:E52_Time-Span"]
76abb8f6-471f-11ee-bc5c-00163e71351b["crm:E41_Appellation"]-->|"crm:P2_has_type"|76abc026-471f-11ee-bc5c-00163e71351b["crm:E55_Type"]
7892caec-471a-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]-->|"crm:P1_is_identified_by"|76abb8f6-471f-11ee-bc5c-00163e71351b["crm:E41_Appellation"]
7892caec-471a-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]-->|"crm:P1_is_identified_by"|b015b84e-471a-11ee-974d-00163e71351b["crm:E42_Identifier"]
7892caec-471a-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]-->|"crm:P129i_is_subject_of"|af71743c-471f-11ee-bc5c-00163e71351b["crm:E33_Linguistic_Object"]
7892caec-471a-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]-->|"crm:P129i_is_subject_of"|c8d02752-471f-11ee-974d-00163e71351b["crm:E30_Right"]
7892caec-471a-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]-->|"crm:P186i_is_produced_by"|38940d7e-471b-11ee-a9ac-00163e71351b["crm:E12_Production"]
7892caec-471a-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]-->|"crm:P2_has_type"|7167cb4c-4728-11ee-a9ac-00163e71351b["crm:E57_Material"]
7892caec-471a-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]-->|"crm:P2_has_type"|908c5cfe-4728-11ee-974d-00163e71351b["crm:E55_Type"]
7892caec-471a-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]-->|"crm:P2i_is_type_of"|9475fd4e-4727-11ee-b0c4-00163e71351b["crm:E22_Man-Made_Object"]
7892caec-471a-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]-->|"crm:P43_has_dimension"|a8804d10-471a-11ee-a9ac-00163e71351b["crm:E54_Dimension"]
908c5cfe-4728-11ee-974d-00163e71351b["crm:E55_Type"]-->|"crm:P2_has_type"|908c60d2-4728-11ee-974d-00163e71351b["crm:E55_Type"]
a8804d10-471a-11ee-a9ac-00163e71351b["crm:E54_Dimension"]-->|"crm:P2_has_type"|a880579c-471a-11ee-a9ac-00163e71351b["crm:E55_Type"]
a8804d10-471a-11ee-a9ac-00163e71351b["crm:E54_Dimension"]-->|"crm:P91_has_unit"|a88058e6-471a-11ee-a9ac-00163e71351b["crm:E58_Measurement_Unit"]
a88051f2-471a-11ee-a9ac-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P2_has_type"|a8805d8c-471a-11ee-a9ac-00163e71351b["crm:E55_Type"]
a88051f2-471a-11ee-a9ac-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P72_has_language"|a8805f62-471a-11ee-a9ac-00163e71351b["crm:E56_Language"]
a88054cc-471a-11ee-a9ac-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P2_has_type"|a88065ac-471a-11ee-a9ac-00163e71351b["crm:E55_Type"]
a88054cc-471a-11ee-a9ac-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P72_has_language"|a8806304-471a-11ee-a9ac-00163e71351b["crm:E56_Language"]
a880579c-471a-11ee-a9ac-00163e71351b["crm:E55_Type"]-->|"crm:P103i_was_intention_of"|a88054cc-471a-11ee-a9ac-00163e71351b["crm:E33_E41_Linguistic_Appellation"]
a88058e6-471a-11ee-a9ac-00163e71351b["crm:E58_Measurement_Unit"]-->|"crm:P103i_was_intention_of"|a88051f2-471a-11ee-a9ac-00163e71351b["crm:E33_E41_Linguistic_Appellation"]
af71743c-471f-11ee-bc5c-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P2_has_type"|af717a0e-471f-11ee-bc5c-00163e71351b["crm:E55_Type"]
af71743c-471f-11ee-bc5c-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P72_has_language"|af717bd0-471f-11ee-bc5c-00163e71351b["crm:E56_Language"]
b015b84e-471a-11ee-974d-00163e71351b["crm:E42_Identifier"]-->|"crm:P2_has_type"|b015be84-471a-11ee-974d-00163e71351b["crm:E55_Type"]
c8d02752-471f-11ee-974d-00163e71351b["crm:E30_Right"]-->|"crm:P1_is_identified_by"|c8d0312a-471f-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]
c8d02752-471f-11ee-974d-00163e71351b["crm:E30_Right"]-->|"crm:P75i_is_possessed_by"|c8d02f54-471f-11ee-974d-00163e71351b["crm:E39_Actor"]
c8d02f54-471f-11ee-974d-00163e71351b["crm:E39_Actor"]-->|"crm:P1_is_identified_by"|c8d035a8-471f-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]
c8d0312a-471f-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P72_has_language"|c8d032f6-471f-11ee-974d-00163e71351b["crm:E56_Language"]
c8d035a8-471f-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P2_has_type"|c8d02ba8-471f-11ee-974d-00163e71351b["crm:E55_Type"]
c8d035a8-471f-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P72_has_language"|c8d03698-471f-11ee-974d-00163e71351b["crm:E56_Language"]
style 51056852-4726-11ee-974d-00163e71351b_s stroke-dasharray: 5
style 38941328-471b-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 38941d82-471b-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 3894194a-471b-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 389410f8-471b-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 38941ca6-471b-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 389415da-471b-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 51056f5a-4726-11ee-974d-00163e71351b_s stroke-dasharray: 5
style 7167d0b0-4728-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 76abbe5a-471f-11ee-bc5c-00163e71351b_s stroke-dasharray: 5
style 76abc026-471f-11ee-bc5c-00163e71351b_s stroke-dasharray: 5
style 76abb8f6-471f-11ee-bc5c-00163e71351b_s stroke-dasharray: 5
style b015b84e-471a-11ee-974d-00163e71351b_s stroke-dasharray: 5
style af71743c-471f-11ee-bc5c-00163e71351b_s stroke-dasharray: 5
style c8d02752-471f-11ee-974d-00163e71351b_s stroke-dasharray: 5
style 38940d7e-471b-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 7167cb4c-4728-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 908c5cfe-4728-11ee-974d-00163e71351b_s stroke-dasharray: 5
style 9475fd4e-4727-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style 800ef872-471f-11ee-b0c4-00163e71351b_s stroke-dasharray: 5
style a8804d10-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style 908c60d2-4728-11ee-974d-00163e71351b_s stroke-dasharray: 5
style a880579c-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style a8805cb0-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style a88059e0-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style a88058e6-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style a8805e72-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style a8805d8c-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style a8805f62-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style a880621e-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style a88065ac-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style a8806304-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style a88054cc-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style a88051f2-471a-11ee-a9ac-00163e71351b_s stroke-dasharray: 5
style af7177de-471f-11ee-bc5c-00163e71351b_s stroke-dasharray: 5
style af717a0e-471f-11ee-bc5c-00163e71351b_s stroke-dasharray: 5
style af717bd0-471f-11ee-bc5c-00163e71351b_s stroke-dasharray: 5
style b015bd80-471a-11ee-974d-00163e71351b_s stroke-dasharray: 5
style b015be84-471a-11ee-974d-00163e71351b_s stroke-dasharray: 5
style c8d0312a-471f-11ee-974d-00163e71351b_s stroke-dasharray: 5
style c8d034b8-471f-11ee-974d-00163e71351b_s stroke-dasharray: 5
style c8d02f54-471f-11ee-974d-00163e71351b_s stroke-dasharray: 5
style c8d035a8-471f-11ee-974d-00163e71351b_s stroke-dasharray: 5
style c8d03210-471f-11ee-974d-00163e71351b_s stroke-dasharray: 5
style c8d032f6-471f-11ee-974d-00163e71351b_s stroke-dasharray: 5
style c8d02d56-471f-11ee-974d-00163e71351b_s stroke-dasharray: 5
style c8d02ba8-471f-11ee-974d-00163e71351b_s stroke-dasharray: 5
style c8d03698-471f-11ee-974d-00163e71351b_s stroke-dasharray: 5
38940d7e-471b-11ee-a9ac-00163e71351b["crm:E12_Production"]-->|"crm:P3_has_note"|38941d82-471b-11ee-a9ac-00163e71351b(rdfs:Literal)
389410f8-471b-11ee-a9ac-00163e71351b["crm:E52_Time-Span"]-->|"crm:P82a_begin_of_the_begin"|38941ca6-471b-11ee-a9ac-00163e71351b(rdfs:Literal)
389410f8-471b-11ee-a9ac-00163e71351b["crm:E52_Time-Span"]-->|"crm:P82b_end_of_the_end"|389415da-471b-11ee-a9ac-00163e71351b(rdfs:Literal)
38941328-471b-11ee-a9ac-00163e71351b["crm:E39_Actor"]-->|"rdfs:label"|38941792-471b-11ee-a9ac-00163e71351b(xsd:string)
3894194a-471b-11ee-a9ac-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|389414f4-471b-11ee-a9ac-00163e71351b(xsd:string)
51056852-4726-11ee-974d-00163e71351b["crm:E57_Material"]-->|"crm:P3_has_note"|51056f5a-4726-11ee-974d-00163e71351b(rdfs:Literal)
51056852-4726-11ee-974d-00163e71351b["crm:E57_Material"]-->|"rdfs:label"|51057202-4726-11ee-974d-00163e71351b(xsd:string)
7167cb4c-4728-11ee-a9ac-00163e71351b["crm:E57_Material"]-->|"crm:P3_has_note"|7167d0b0-4728-11ee-a9ac-00163e71351b(rdfs:Literal)
7167cb4c-4728-11ee-a9ac-00163e71351b["crm:E57_Material"]-->|"rdfs:label"|7167d27c-4728-11ee-a9ac-00163e71351b(xsd:string)
76abb8f6-471f-11ee-bc5c-00163e71351b["crm:E41_Appellation"]-->|"crm:P190_has_symbolic_content"|76abbe5a-471f-11ee-bc5c-00163e71351b(rdfs:Literal)
76abc026-471f-11ee-bc5c-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|76abc1a2-471f-11ee-bc5c-00163e71351b(xsd:string)
7892caec-471a-11ee-a9ac-00163e71351b["crm:E99_Product_Type"]-->|"crm:P3_has_note"|800ef872-471f-11ee-b0c4-00163e71351b(rdfs:Literal)
908c5cfe-4728-11ee-974d-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|908c621c-4728-11ee-974d-00163e71351b(xsd:string)
908c60d2-4728-11ee-974d-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|908c6316-4728-11ee-974d-00163e71351b(xsd:string)
a8804d10-471a-11ee-a9ac-00163e71351b["crm:E54_Dimension"]-->|"crm:P3_has_note"|a8805cb0-471a-11ee-a9ac-00163e71351b(rdfs:Literal)
a8804d10-471a-11ee-a9ac-00163e71351b["crm:E54_Dimension"]-->|"crm:P90_has_value"|a88059e0-471a-11ee-a9ac-00163e71351b(rdfs:Literal)
a88051f2-471a-11ee-a9ac-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P190_has_symbolic_content"|a8805e72-471a-11ee-a9ac-00163e71351b(rdfs:Literal)
a88054cc-471a-11ee-a9ac-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P190_has_symbolic_content"|a880621e-471a-11ee-a9ac-00163e71351b(rdfs:Literal)
a880579c-471a-11ee-a9ac-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|a8805ada-471a-11ee-a9ac-00163e71351b(xsd:string)
a88058e6-471a-11ee-a9ac-00163e71351b["crm:E58_Measurement_Unit"]-->|"rdfs:label"|a8805bc0-471a-11ee-a9ac-00163e71351b(xsd:string)
a8805d8c-471a-11ee-a9ac-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|a880612e-471a-11ee-a9ac-00163e71351b(xsd:string)
a8805f62-471a-11ee-a9ac-00163e71351b["crm:E56_Language"]-->|"rdfs:label"|a880603e-471a-11ee-a9ac-00163e71351b(xsd:string)
a8806304-471a-11ee-a9ac-00163e71351b["crm:E56_Language"]-->|"rdfs:label"|a88063e0-471a-11ee-a9ac-00163e71351b(xsd:string)
a88065ac-471a-11ee-a9ac-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|a88064d0-471a-11ee-a9ac-00163e71351b(xsd:string)
af71743c-471f-11ee-bc5c-00163e71351b["crm:E33_Linguistic_Object"]-->|"crm:P190_has_symbolic_content"|af7177de-471f-11ee-bc5c-00163e71351b(rdfs:Literal)
af717a0e-471f-11ee-bc5c-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|af717914-471f-11ee-bc5c-00163e71351b(xsd:string)
af717bd0-471f-11ee-bc5c-00163e71351b["crm:E56_Language"]-->|"rdfs:label"|af717af4-471f-11ee-bc5c-00163e71351b(xsd:string)
b015b84e-471a-11ee-974d-00163e71351b["crm:E42_Identifier"]-->|"crm:P190_has_symbolic_content"|b015bd80-471a-11ee-974d-00163e71351b(rdfs:Literal)
b015be84-471a-11ee-974d-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|b015bc40-471a-11ee-974d-00163e71351b(xsd:string)
c8d02752-471f-11ee-974d-00163e71351b["crm:E30_Right"]-->|"crm:P3_has_note"|c8d034b8-471f-11ee-974d-00163e71351b(rdfs:Literal)
c8d02ba8-471f-11ee-974d-00163e71351b["crm:E55_Type"]-->|"rdfs:label"|c8d02e64-471f-11ee-974d-00163e71351b(xsd:string)
c8d0312a-471f-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P190_has_symbolic_content"|c8d03210-471f-11ee-974d-00163e71351b(rdfs:Literal)
c8d032f6-471f-11ee-974d-00163e71351b["crm:E56_Language"]-->|"rdfs:label"|c8d033d2-471f-11ee-974d-00163e71351b(xsd:string)
c8d035a8-471f-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-->|"crm:P190_has_symbolic_content"|c8d02d56-471f-11ee-974d-00163e71351b(rdfs:Literal)
c8d03698-471f-11ee-974d-00163e71351b["crm:E56_Language"]-->|"rdfs:label"|c8d0303a-471f-11ee-974d-00163e71351b(xsd:string)
51056852-4726-11ee-974d-00163e71351b["crm:E57_Material"]-.-51056852-4726-11ee-974d-00163e71351b_s(["Production Material"])
38941328-471b-11ee-a9ac-00163e71351b["crm:E39_Actor"]-.-38941328-471b-11ee-a9ac-00163e71351b_s(["Production Carried Out By"])
38941d82-471b-11ee-a9ac-00163e71351b["rdfs:Literal"]-.-38941d82-471b-11ee-a9ac-00163e71351b_s(["Production Note"])
3894194a-471b-11ee-a9ac-00163e71351b["crm:E55_Type"]-.-3894194a-471b-11ee-a9ac-00163e71351b_s(["Production Technique Type"])
389410f8-471b-11ee-a9ac-00163e71351b["crm:E52_Time-Span"]-.-389410f8-471b-11ee-a9ac-00163e71351b_s(["Production Time-Span"])
38941ca6-471b-11ee-a9ac-00163e71351b["rdfs:Literal"]-.-38941ca6-471b-11ee-a9ac-00163e71351b_s(["Production Time-Span Begin"])
389415da-471b-11ee-a9ac-00163e71351b["rdfs:Literal"]-.-389415da-471b-11ee-a9ac-00163e71351b_s(["Production Time-Span End"])
51056f5a-4726-11ee-974d-00163e71351b["rdfs:Literal"]-.-51056f5a-4726-11ee-974d-00163e71351b_s(["Production Material Note"])
7167d0b0-4728-11ee-a9ac-00163e71351b["rdfs:Literal"]-.-7167d0b0-4728-11ee-a9ac-00163e71351b_s(["Material Note"])
76abbe5a-471f-11ee-bc5c-00163e71351b["rdfs:Literal"]-.-76abbe5a-471f-11ee-bc5c-00163e71351b_s(["Appellation Content"])
76abc026-471f-11ee-bc5c-00163e71351b["crm:E55_Type"]-.-76abc026-471f-11ee-bc5c-00163e71351b_s(["Appellation Type"])
76abb8f6-471f-11ee-bc5c-00163e71351b["crm:E41_Appellation"]-.-76abb8f6-471f-11ee-bc5c-00163e71351b_s(["Appellation"])
b015b84e-471a-11ee-974d-00163e71351b["crm:E42_Identifier"]-.-b015b84e-471a-11ee-974d-00163e71351b_s(["Identifier"])
af71743c-471f-11ee-bc5c-00163e71351b["crm:E33_Linguistic_Object"]-.-af71743c-471f-11ee-bc5c-00163e71351b_s(["Description"])
c8d02752-471f-11ee-974d-00163e71351b["crm:E30_Right"]-.-c8d02752-471f-11ee-974d-00163e71351b_s(["Right"])
38940d7e-471b-11ee-a9ac-00163e71351b["crm:E12_Production"]-.-38940d7e-471b-11ee-a9ac-00163e71351b_s(["Production"])
7167cb4c-4728-11ee-a9ac-00163e71351b["crm:E57_Material"]-.-7167cb4c-4728-11ee-a9ac-00163e71351b_s(["Material"])
908c5cfe-4728-11ee-974d-00163e71351b["crm:E55_Type"]-.-908c5cfe-4728-11ee-974d-00163e71351b_s(["Type"])
9475fd4e-4727-11ee-b0c4-00163e71351b["crm:E22_Man-Made_Object"]-.-9475fd4e-4727-11ee-b0c4-00163e71351b_s(["Item"])
800ef872-471f-11ee-b0c4-00163e71351b["rdfs:Literal"]-.-800ef872-471f-11ee-b0c4-00163e71351b_s(["Note"])
a8804d10-471a-11ee-a9ac-00163e71351b["crm:E54_Dimension"]-.-a8804d10-471a-11ee-a9ac-00163e71351b_s(["Dimension"])
908c60d2-4728-11ee-974d-00163e71351b["crm:E55_Type"]-.-908c60d2-4728-11ee-974d-00163e71351b_s(["Type Type"])
a880579c-471a-11ee-a9ac-00163e71351b["crm:E55_Type"]-.-a880579c-471a-11ee-a9ac-00163e71351b_s(["Dimension Type"])
a8805cb0-471a-11ee-a9ac-00163e71351b["rdfs:Literal"]-.-a8805cb0-471a-11ee-a9ac-00163e71351b_s(["Dimension Note"])
a88059e0-471a-11ee-a9ac-00163e71351b["rdfs:Literal"]-.-a88059e0-471a-11ee-a9ac-00163e71351b_s(["Dimension Value"])
a88058e6-471a-11ee-a9ac-00163e71351b["crm:E58_Measurement_Unit"]-.-a88058e6-471a-11ee-a9ac-00163e71351b_s(["Dimension Unit"])
a8805e72-471a-11ee-a9ac-00163e71351b["rdfs:Literal"]-.-a8805e72-471a-11ee-a9ac-00163e71351b_s(["Dimension Unit Linguistic Appellation Content"])
a8805d8c-471a-11ee-a9ac-00163e71351b["crm:E55_Type"]-.-a8805d8c-471a-11ee-a9ac-00163e71351b_s(["Dimension Unit Linguistic Appellation Type"])
a8805f62-471a-11ee-a9ac-00163e71351b["crm:E56_Language"]-.-a8805f62-471a-11ee-a9ac-00163e71351b_s(["Dimension Unit Linguistic Appellation Language"])
a880621e-471a-11ee-a9ac-00163e71351b["rdfs:Literal"]-.-a880621e-471a-11ee-a9ac-00163e71351b_s(["Dimension Type Linguistic Appellation Content"])
a88065ac-471a-11ee-a9ac-00163e71351b["crm:E55_Type"]-.-a88065ac-471a-11ee-a9ac-00163e71351b_s(["Dimension Type Linguistic Appellation Type"])
a8806304-471a-11ee-a9ac-00163e71351b["crm:E56_Language"]-.-a8806304-471a-11ee-a9ac-00163e71351b_s(["Dimension Type Linguistic Appellation Language"])
a88054cc-471a-11ee-a9ac-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-.-a88054cc-471a-11ee-a9ac-00163e71351b_s(["Dimension Type Linguistic Appellation"])
a88051f2-471a-11ee-a9ac-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-.-a88051f2-471a-11ee-a9ac-00163e71351b_s(["Dimension Unit Linguistic Appellation"])
af7177de-471f-11ee-bc5c-00163e71351b["rdfs:Literal"]-.-af7177de-471f-11ee-bc5c-00163e71351b_s(["Description Content"])
af717a0e-471f-11ee-bc5c-00163e71351b["crm:E55_Type"]-.-af717a0e-471f-11ee-bc5c-00163e71351b_s(["Description Type"])
af717bd0-471f-11ee-bc5c-00163e71351b["crm:E56_Language"]-.-af717bd0-471f-11ee-bc5c-00163e71351b_s(["Description Language"])
b015bd80-471a-11ee-974d-00163e71351b["rdfs:Literal"]-.-b015bd80-471a-11ee-974d-00163e71351b_s(["Identifier Content"])
b015be84-471a-11ee-974d-00163e71351b["crm:E55_Type"]-.-b015be84-471a-11ee-974d-00163e71351b_s(["Identifier Type"])
c8d0312a-471f-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-.-c8d0312a-471f-11ee-974d-00163e71351b_s(["Right Appellation"])
c8d034b8-471f-11ee-974d-00163e71351b["rdfs:Literal"]-.-c8d034b8-471f-11ee-974d-00163e71351b_s(["Right Note"])
c8d02f54-471f-11ee-974d-00163e71351b["crm:E39_Actor"]-.-c8d02f54-471f-11ee-974d-00163e71351b_s(["Right Holder"])
c8d035a8-471f-11ee-974d-00163e71351b["crm:E33_E41_Linguistic_Appellation"]-.-c8d035a8-471f-11ee-974d-00163e71351b_s(["Right Holder Appellation"])
c8d03210-471f-11ee-974d-00163e71351b["rdfs:Literal"]-.-c8d03210-471f-11ee-974d-00163e71351b_s(["Right Appellation Content"])
c8d032f6-471f-11ee-974d-00163e71351b["crm:E56_Language"]-.-c8d032f6-471f-11ee-974d-00163e71351b_s(["Right Appellation Language"])
c8d02d56-471f-11ee-974d-00163e71351b["rdfs:Literal"]-.-c8d02d56-471f-11ee-974d-00163e71351b_s(["Right Holder Appellation Content"])
c8d02ba8-471f-11ee-974d-00163e71351b["crm:E55_Type"]-.-c8d02ba8-471f-11ee-974d-00163e71351b_s(["Right Holder Appellation Type"])
c8d03698-471f-11ee-974d-00163e71351b["crm:E56_Language"]-.-c8d03698-471f-11ee-974d-00163e71351b_s(["Right Holder Appellation Language"])
style 38940d7e-471b-11ee-a9ac-00163e71351b fill:#5DAEEC
style 389410f8-471b-11ee-a9ac-00163e71351b fill:#76A5AF
style 38941328-471b-11ee-a9ac-00163e71351b fill:#ffc0cb
style 389414f4-471b-11ee-a9ac-00163e71351b fill:#D3D3D3
style 389415da-471b-11ee-a9ac-00163e71351b fill:#D3D3D3
style 38941792-471b-11ee-a9ac-00163e71351b fill:#D3D3D3
style 3894194a-471b-11ee-a9ac-00163e71351b fill:#ffa500
style 38941ca6-471b-11ee-a9ac-00163e71351b fill:#D3D3D3
style 38941d82-471b-11ee-a9ac-00163e71351b fill:#D3D3D3
style 51056852-4726-11ee-974d-00163e71351b fill:#ffa500
style 51056f5a-4726-11ee-974d-00163e71351b fill:#D3D3D3
style 51057202-4726-11ee-974d-00163e71351b fill:#D3D3D3
style 7167cb4c-4728-11ee-a9ac-00163e71351b fill:#ffa500
style 7167d0b0-4728-11ee-a9ac-00163e71351b fill:#D3D3D3
style 7167d27c-4728-11ee-a9ac-00163e71351b fill:#D3D3D3
style 76abb8f6-471f-11ee-bc5c-00163e71351b fill:#EEE8AA
style 76abbe5a-471f-11ee-bc5c-00163e71351b fill:#D3D3D3
style 76abc026-471f-11ee-bc5c-00163e71351b fill:#ffa500
style 76abc1a2-471f-11ee-bc5c-00163e71351b fill:#D3D3D3
style 7892caec-471a-11ee-a9ac-00163e71351b fill:#ffff00
style 800ef872-471f-11ee-b0c4-00163e71351b fill:#D3D3D3
style 908c5cfe-4728-11ee-974d-00163e71351b fill:#ffa500
style 908c60d2-4728-11ee-974d-00163e71351b fill:#ffa500
style 908c621c-4728-11ee-974d-00163e71351b fill:#D3D3D3
style 908c6316-4728-11ee-974d-00163e71351b fill:#D3D3D3
style 9475fd4e-4727-11ee-b0c4-00163e71351b fill:#B0927A
style a8804d10-471a-11ee-a9ac-00163e71351b fill:#808080
style a88051f2-471a-11ee-a9ac-00163e71351b fill:#ffff00
style a88054cc-471a-11ee-a9ac-00163e71351b fill:#ffff00
style a880579c-471a-11ee-a9ac-00163e71351b fill:#ffa500
style a88058e6-471a-11ee-a9ac-00163e71351b fill:#ffa500
style a88059e0-471a-11ee-a9ac-00163e71351b fill:#D3D3D3
style a8805ada-471a-11ee-a9ac-00163e71351b fill:#D3D3D3
style a8805bc0-471a-11ee-a9ac-00163e71351b fill:#D3D3D3
style a8805cb0-471a-11ee-a9ac-00163e71351b fill:#D3D3D3
style a8805d8c-471a-11ee-a9ac-00163e71351b fill:#ffa500
style a8805e72-471a-11ee-a9ac-00163e71351b fill:#D3D3D3
style a8805f62-471a-11ee-a9ac-00163e71351b fill:#ffa500
style a880603e-471a-11ee-a9ac-00163e71351b fill:#D3D3D3
style a880612e-471a-11ee-a9ac-00163e71351b fill:#D3D3D3
style a880621e-471a-11ee-a9ac-00163e71351b fill:#D3D3D3
style a8806304-471a-11ee-a9ac-00163e71351b fill:#ffa500
style a88063e0-471a-11ee-a9ac-00163e71351b fill:#D3D3D3
style a88064d0-471a-11ee-a9ac-00163e71351b fill:#D3D3D3
style a88065ac-471a-11ee-a9ac-00163e71351b fill:#ffa500
style af71743c-471f-11ee-bc5c-00163e71351b fill:#ffff00
style af7177de-471f-11ee-bc5c-00163e71351b fill:#D3D3D3
style af717914-471f-11ee-bc5c-00163e71351b fill:#D3D3D3
style af717a0e-471f-11ee-bc5c-00163e71351b fill:#ffa500
style af717af4-471f-11ee-bc5c-00163e71351b fill:#D3D3D3
style af717bd0-471f-11ee-bc5c-00163e71351b fill:#ffa500
style b015b84e-471a-11ee-974d-00163e71351b fill:#EEE8AA
style b015bc40-471a-11ee-974d-00163e71351b fill:#D3D3D3
style b015bd80-471a-11ee-974d-00163e71351b fill:#D3D3D3
style b015be84-471a-11ee-974d-00163e71351b fill:#ffa500
style c8d02752-471f-11ee-974d-00163e71351b fill:#ffff00
style c8d02ba8-471f-11ee-974d-00163e71351b fill:#ffa500
style c8d02d56-471f-11ee-974d-00163e71351b fill:#D3D3D3
style c8d02e64-471f-11ee-974d-00163e71351b fill:#D3D3D3
style c8d02f54-471f-11ee-974d-00163e71351b fill:#ffc0cb
style c8d0303a-471f-11ee-974d-00163e71351b fill:#D3D3D3
style c8d0312a-471f-11ee-974d-00163e71351b fill:#ffff00
style c8d03210-471f-11ee-974d-00163e71351b fill:#D3D3D3
style c8d032f6-471f-11ee-974d-00163e71351b fill:#ffa500
style c8d033d2-471f-11ee-974d-00163e71351b fill:#D3D3D3
style c8d034b8-471f-11ee-974d-00163e71351b fill:#D3D3D3
style c8d035a8-471f-11ee-974d-00163e71351b fill:#ffff00
style c8d03698-471f-11ee-974d-00163e71351b fill:#ffa500
```
