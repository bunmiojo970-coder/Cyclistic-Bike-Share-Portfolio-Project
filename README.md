# Cyclistic-Bike-Share-Portfolio-Project
This is analysis in SQL to identify trends in how annual and casual riders use cyclistic bikes.
SELECT rideable_type,
   COUNT (rideable_type) AS number_of_type,
   AVG (ride_length_seconds) AS avg_rls
 FROM `extended-ward-451121-a9.Cyclistic_Bike_Share.2025 UNION ALL casual`
GROUP BY rideable_type
ORDER BY avg_rls desc;
