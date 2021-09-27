# 2021_IBM_Code_Challange_SocialDistanceMonitoringSystem
## SOCIAL DISTANCE MONITORING SYSTEM

Social distancing in Real Time using live video stream

  In the current pandemic scenario of COVID-19 disease, it is essential to reduce close physical contact. Therefore, social distancing is thought to be an adequate precaution against the spread of the pandemic virus.
  
**PROBLEM STATEMENT**

Many healthcare organizations, scientists, and medical professionals are searching for proper vaccines and medicines to overcome this deadly virus.To stop the virus spread, the global community is looking for alternate ways.The virus mainly spreads those who are in close contact with each other for a long period.Therefore, it is necessary to maintain at least 6 feet distance from others, even if people do not have any symptoms.

Therefore to overcome the virus spread, by minimizing the physical contacts of humans with the social distancing measures.

To ensure the social distancing protocol in public areas,we developed social distancing detector using YOLOv3 model.It can monitor if the people are keeping a safe distance from each other by analyzing real time video streams.

**FEATURES**

* The output of YOLOv3 object detection is used to compute the centroid of the bounding box.
* Compute the Euclidean distance between all pairs of centroids.To check, either the      calculated distance comes under the violation set or not.
* The bounding box's color is formerly initialized as green. If the bounding box comes under the violation set, its color is updated to red.
* Display information's of total number of social distancing violations, safe count, low risk count, high risk count.

**USE CASE**

* monitor number of people in real time and send alert to operators if distance more than limit.
* Act as a tackle to Covid-19.










.



   
