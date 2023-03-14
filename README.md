# Pollen-Types-in-Madrid (json Dataset Cleaning and Basic Analysis)
 
All big cities in the world, including Madrid, are exerting big efforts towards the availability of open data for its people. Variety of data is incredibly huge, involving different areas, such as environment, transportation, tourism and public health. An area of interest, from health point of view, is the increase of allergic reactions during pollen season. The government of Madrid's Community has availed public data sets with the content of pollen in air, in terms of grains per cubic meter.

This article will show the usage of Python and its powerful library Pandas to read, explore and clean the subject pollen data set, to generate a useful data frame which can be further used for analysis.

The dataset contains values obtained from 11 different sensors ("captador") located in Madrid:

1. ALCA (Alcalá de Henares)
2. ALCO (Alcobendas)
3. ALER (Madrid - Salamanca Neighborhood)
4. ARAN (Aranjuez)
5. AYTM (Madrid - Arganzuela)
6. COSL (Coslada)
7. FACF (Madrid - Ciudad Universitaria)
8. GETA (Getafe)
9. LEGA (Leganes, out of service)
10. ROZA (Las Rozas)
11. VILL (Collado Villalba)

Total 27 types of pollen are part of the data under analysis:
1. Abedul
2. Aligustre
3. Aliso
4. Arce
5. Artemisia
6. Castaño
7. Compuestas
8. Corylus
9. Cupresáceas/Taxáceas
10. Ericaceae
11. Eucalipto
12. Fresno
13. Gramíneas
14. Moreras
15. Olivo
16. Olmos
17. Otros
18. Pinos
19. Plantago
20. Plátano de paseo
21. PNI (Polen no identificado)
22. Poulus
23. Quenopodiáceas/Amarantáceas
24. Quercus
25. Rumex (Acederas)
26. Sauces
27. Urticaceae (Ortigas)

Data was collected on daily basis, starting from from Dec-12-2022 to Mar-05-2023.
