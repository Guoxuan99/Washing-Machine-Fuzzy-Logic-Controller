# Washing-Machine-Fuzzy-Logic-Controller
2021/2022 sem 1 - Fuzzy Logic Group Assignment - Washing Machine Fuzzy Logic Controller - A fuzzy logic controller system of controlling the washing machine with 5 inputs and 5 outputs by using SKFuzzy.


Research Paper referenced: https://doi.org/10.5120/ijca2016911846


Inputs:


The greasiness of the dirt present on the clothes (dirt_type), the amount of dirt present on the clothes (cloth_dirtiness), the mass of the clothes (cloth_mass), the sensitivity of the clothes in water absorption (cloth_sensitivity), and the hardness of the water used for washing (water_hardness).


Outputs:


The washing time required (wash_time), the washing machine spinning speed (wash_speed), the amount of water needed (water_amount), the amount of detergent needed (detergent_amount), and the temperature of water (water_temperature).


Some membership functions:


![Screenshot 2022-01-28 172217](https://user-images.githubusercontent.com/65883921/151521159-ada26007-8d6f-40d7-9e17-4dc8c07de74f.png)


This system used 27 rules in the inference engine to determine the aggregated output and the defuzzification method used is "Centroid". To provide more usability, we developed an UI so user can interact with the program easily. This is also one of the benefits of using SKFuzzy since it is easy to be integrated with TKinter library.


![Screenshot 2022-01-28 172303](https://user-images.githubusercontent.com/65883921/151521166-c5b8ac76-e0ba-438f-a16c-cf7eb193b11b.png)
