
# **Earthquake Damage Prediction**
-----------
## **Business Case-Study**

Earthquakes are natural disasters with the potential to cause widespread devastation, leading to loss of life, property damage, and disruption of
essential services. Traditional seismic design and retrofitting methods have limitations in predicting and preventing the full extent of damage.
Hence, there is a critical need for innovative solutions that leverage advanced technologies to enhance predictive capabilities of earthquake damage.
In recent years, the frequency and intensity of earthquakes have posed a significant threat to urban infrastructure, causing substantial
economic losses and human suffering.

So, This business case study explores the development and implementation of an advanced earthquake damage prediction system aimed at mitigating the
impact of seismic events on buildings infrastructure in earthquake-prone regions. The primary objective of this business case is to propose the
development and deployment of an earthquake damage prediction system that utilizes six different types of machine learning algorithms including:
Logistic Regression, K-Nearest Neighbors, Decision Trees, Random Forest,
Gradient Boosting, XG-Boosting.

Benefit from this model: Improved Urban Planning, Enhanced Public Safety, Reduced Economic Losses caused by earthquakes.



--------
## **Dataset Description**

This dataset consists total 40 features with 260601 rows.

**Target explained** here:

1) Damage_grade: This presents the level of damage grade affected at the time of earthquake.(1,2,3 represents low damage, medium amount of damage,almost complete destruction respectively)

**Others Features** are explained here:

1) building_id: It represents each building units.

2) geo_level_1_id: This is the highest level of geographic region classification. It can have values in the range of 0 to 30. Each value typically represents a broad region or country.

3) geo_level_2_id: This is a more detailed sub-region within the geo_level_1_id. It can have values in the range of 0 to 1427, which provides more specific information about the region where the building is located.

4) geo_level_3_id: This is the most specific sub-region classification. It can have values in the range of 0 to 12567, offering the most detailed information about the geographic location of the building.

5) count_floors_pre_eq: Number of floors in the building before the earthquake.

6) age: Age of the building in years.

7) area_percentage: Normalized area of the building footprint.

8) height_percentage: Normalized height of the building footprint.

9) land_surface_condition: Surface condition of the land where the building was built. Possible values:(n: Normal Surface Condition, o: Poor Surface Condition, t: Unusual Surface Condition)

10) foundation_type: Type of foundation used in the building. Possible values:(h: Hard or Concrete, i: Similartohard, r: Rubble stone, u: Bamboo or Timber, w: Other or Wooden)

11) roof_type: Type of roof used in building. Possible values:(n: No roof, q: Quasi-flat roof., x: Traditional roof structure)

12) ground_floor_type: Type of the ground floor. Possible values:(f:Floorslab, m: Mud, v: Other, x: Timber, z: Bamboo)

13) other_floor_type: Type of constructions used in higher than the ground floors (except roof). Possible values:(j: Jackets, q: Quasi-adobe, s: Wooden or Timber, x: Unknown)

14) position: Position of the building while construction. Possible values:(j: Jutting, o: Onesideattached, s: Semi-detached or Attached-2 side, t: Terraced or Linear)

15) plan_configuration: Building plan configuration. Possible values:(a:Rectangular, c: L-shaped, d: T-shaped, f: Wing-shaped, m: Multiple or Complex, n: Square-shaped, o: Other or Unique,q: H-shaped, s: U-shaped, u: E-shaped)

16) has_superstructure_adobe_mud: Flag variable that indicates if the superstructure was made of Adobe/Mud.

17) has_superstructure_mud_mortar_stone: Flag variable that indicates if the superstructure was made of Mud Mortar-Stone.

18) has_superstructure_stone_flag: Flag variable that indicates if the superstructure was made of Stone.

19) has_superstructure_cement_mortar_stone: Flag variable that indicates if the superstructure was made of Cement Mortar-Stone.

20) has_superstructure_mud_mortar_brick: Flag variable that indicates if the superstructure was made of Mud Mortar-Brick.

21) has_superstructure_cement_mortar_brick: Flag variable that indicates if the superstructure was made of Cement Mortar - Brick.

22) has_superstructure_timber: Flag variable that indicates if the superstructure was made of Timber.

23) has_superstructure_bamboo: Flag variable that indicates if the superstructure was made of Bamboo.

24) has_superstructure_rc_non_engineered: Flag variable that indicates if the superstructure was made of non-engineered reinforced concrete.

25) has_superstructure_rc_engineered: Flag variable that indicates if the superstructure was made of engineered reinforced concrete.

26) has_superstructure_other: Flag variable that indicates if the superstructure was made of any other material.

27) legal_ownership_status: Legal ownership status of the land where building was built. Possible values:(a: Own or Private ownership, r: Rented, v: Government-owned, w: Institutional ownership)

28) count_families: Number of families that live in the building.

29) has_secondary_use: Flag variable that indicates if the building was used for any secondary purpose.

30) has_secondary_use_agriculture: Flag variable that indicates if the building was used for agricultural purposes.

31) has_secondary_use_hotel: Flag variable that indicates if the building was used as a hotel.

32) has_secondary_use_rental: Flag variable that indicates if the building was used for rental purposes.

33) has_secondary_use_institution: Flag variable that indicates if the building was used as a location of any institution.

34) has_secondary_use_school: Flag variable that indicates if the building was used as a school.

35) has_secondary_use_industry: Flag variable that indicates if the building was used for industrial purposes.

36) has_secondary_use_health_post: Flag variable that indicates if the building was used as a health post.

37) has_secondary_use_gov_office: Flag variable that indicates if the building was used has a government office.

38) has_secondary_use_use_police: Flag variable that indicates if the building was used as a police station.

39) has_secondary_use_other: Flag variable that indicates if the building was secondarily used for other purposes.



-----------
### Categorical Features with respect to Damage Grade
![image](https://github.com/TrushalPatel0/Earthquake/assets/144200919/6cc6651b-a173-4b57-9fd9-68023bfbb636)

----------
### Numerical Features with respect to Damage Grade
![image](https://github.com/TrushalPatel0/Earthquake/assets/144200919/5921cdff-c278-430c-a3a6-d639818a69d4)



--------
## **Machine Learning Algorithms**
1) Logistic Regression

2) K-Nearest Neighbors

3) Decision Trees

4) Random Forest

5) Gradient Boosting

6) XG-Boosting


----------------------
### Model Comparison Report
<img width="441" alt="image" src="https://github.com/TrushalPatel0/Earthquake/assets/144200919/ed464073-3ada-4db2-82b1-355a546223af">




--------
## **Suggestions to the Seismologists**:
1) Foundation type should be similar to hard:
This might suggest that the foundation is similar to a hard or concrete foundation but not exactly the same. It could include variations or alternative materials that share characteristics with traditional hard foundations.

2) Roof type should be traditional:
This suggests that the building has a traditional roof structure. Traditional roofs can come in various styles, such as gable, hip, mansard, or shed roofs, depending on the architectural design and regional building practices.

3) Ground floor type should be others:
It represents an option not covered by the specific categories listed. It could include various materials or construction methods for the ground floor that do not fit into the other categories such as Floorslab, Mud, Timber, Bamboo.

4) Other floor type should be wooden:
It suggests that the construction of the higher floors involves the use of wood or timber. Wooden construction is common in many building practices, providing a lightweight and versatile material for framing and structural support.

5) Plan configuration should be L shaped:
The building plan is in the shape of an "L". L-shaped configurations are often used to provide variations in space and create different zones within a building.

6) Legal ownership status should be private:
This indicates that the land where the building is constructed is privately owned.

7) Age of building:
After 15 years there would be high chance of more damage so we have to do renovation of the building.




--------
## **Challenges faced**:
We did all the steps such as Basic info, EDA, Preprocessing, Model creation. But we have to face challenges mostly in EDA part, because there are total 40 features in which we have to perform feature extraction by analysing the EDA part from different graphs. Atlast we finally reduced 40 features into 17 features. And then apply different six models and shows their Accuracy in Model Comparision Report.
