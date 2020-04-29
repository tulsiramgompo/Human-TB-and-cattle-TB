# Human-TB-and-cattle-TB
This projects deals with the interaction of cattle and human beings which is associated to development of zoonotic TB in people.

## Codes for calculating tuberculin tests

cattle_tb$herd_size<-as.factor(cattle_tb$herd_size)
table(cattle_tb$tuberculin_classification)
table(cattle_tb$rapid_test_final)

table(cattle_tb$age_of_cattle,cattle_tb$tuberculin_classification)
table(cattle_tb$herd_size,cattle_tb$tuberculin_classification)
table(cattle_tb$body_condition,cattle_tb$tuberculin_classification)
table(cattle_tb$husbandry_practice,cattle_tb$tuberculin_classification)
table(cattle_tb$breed,cattle_tb$tuberculin_classification)
table(cattle_tb$coughing_history,cattle_tb$tuberculin_classification)
table(cattle_tb$animal_origin,cattle_tb$tuberculin_classification)
