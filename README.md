# CASTRA-DEMO-DHS
Demonstration of CASTRA Machine learning algorithms 

Ref: D. M. Shila et. al, A multi-faceted approach to user authentication for mobile devices — Using human movement, usage, and location patterns

The video 1 and video 2 shows how CASTRA Machine Learning Algorithms performance and fusion algorithms.
        The left side of the video (on playing) shows the various behavioral traits used by CASTRA:
         Gait: Walking Patterns learned from accelerometer, gyroscope data collected from mobile device 
         Location: Whether the user is seen in a frequently visited or untrusted place; these patterns are learned automatically from the           GPS data
         Biometrics: The time after the initial biometrics and based on the proximity of device with the user i.e., if the device is in            pocket or on table. 
         Fused scores: All these scores are fused together using a weight based metric to compute the final trust score. 
         
Video 1: User walks with the phone on his pocket; Performed his biometrics before the experiment starts; 
         User is in untrusted place, his biometrics is decreasing, but as his gait score is good, the fused score is MEDIUM. As he walks            towards the building, the GPS score increases and the trust score changes to HIGH. When user enters the building, his gait                changes, the trust score drops to medium. When the phone is placed on table, algorithms detect it and set to LOW. Towards the              last, an unknown person picks up the phone and the trust score stays medium.  
               
Video 2: Demonstrates friendly attack, where the actual owner hands off the device to his friend, algorithm detects it from gait patterns and set the trust score to LOW.        
         
         
