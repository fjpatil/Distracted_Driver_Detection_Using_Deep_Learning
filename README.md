# Deep-Learning

# Approach
<p align="justify">
Initial implementation started with CNN algorithm from scratch and identified miss classification among testing dataset even though the accuracy was high. So, decided to continue with Transfer Learning approach. We have different type transfer learning algorithms available but I implemented this project with VGG16 and Mobilenet, among these two according to me preferred choice would be Mobilenet because it is specifically developed with computational restraints in mind which suit the application in the car the best and it had the lowest log loss.
</p>

# Aim of the Project

<p align="justify">
During the time spent recognizing the real mishap chance we ran over a few variables which are genuine most influenced reasons for mishap in that one of the references we discovered is about Driver Distraction re-search completed by European Commission, DG MOVE which was basically distinguished that Driver Distraction is a most influenced factor for the majority of the mishaps in Europe. This venture analyzed the nature and size of the driver distraction in road safety in the EU (particularly as far as cell phones), and those countermeasures which can be utilized to bring down its effect. A writing audit, a survey of factual distributions on national street injury information, a partner study, meetings and workshops, a survey of innovation improvements and a multi-model’s examination were embraced. The examination inferred that 10-30% of road mishaps in the EU could have interruption as a contributory factor, despite the fact that confinements of the information accessible mean this figure requires further approval. An enormous number of innovation advancements were recognized that get the opportunity to affect on the issue, both as far as hidden advances in future cell phones, and regarding vehicle security frameworks. Nine proposals are given, regarding information prerequisites, innovation, mindfulness and training, and gauges; these suggestions depended on the multi-standards examination of expenses and advantages.  

In this study, TRL, TNO and Rapp Trans undertook a number of tasks to answer the following research questions:   
•	What is the nature and size of the distraction problem in road safety in the EU?  
•	Which approaches and countermeasures have been used to reduce the road injury burden of distraction?  
•	Which ‘best practice’ approaches should be used by EU states in their efforts to reduce the road injury burden of distraction (including an assessment of costs and benefits)?  </p>
<p align="justify">
This research study finally concluded based on the statistical data from different EU countries proposed that many technological developments like collision warning systems, Speech based infotainment systems, Night vision and aware programs like public campaigns, Pedestrian distraction study, Good driving behavior etc. By the above-mentioned solutions road mishap can be reduces to significant numbers.  
</p>  

Here I took the StateFarm dataset which contains snapshots from a video captured by a camera mounted in the car. Training set has ~22.4 K samples with equal distribution among the classes and 79.7 K unlabeled test samples.    
There are 10 classes including safe driving in the dataset:    
•	c0 Safe driving.  
•	c1 Texting (right hand).  
•	c2 Talking on the phone (right hand).  
•	c3 Texting (left hand).  
•	c4 Talking on the phone (left hand).  
•	c5 Operating the radio.  
•	c6 Drinking.  
•	c7 Reaching behind.  
•	c8 Hair and makeup.  
•	c9 Talking to passenger(s).  

