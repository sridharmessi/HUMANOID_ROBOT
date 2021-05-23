# HUMANOID_ROBOT
This project will help the elderly people to get essential material and non- essential material from set of materilas or object surrounded nearby.
Agend of project or overview of project as follows
bascically the robot is composed of three parts 
 -----------------------------------------------   head-(rotobic head)
 -----------------------------------------------   hand-(Robotic arm)
  -----------------------------------------------  leg(Robotic leg)
  
  
  Robotic head 
  where we use computer vision algrothuim to find the what kind of object is it and seperate the object the into flag 0 and flag 1
  we use yolo algrothium to find the object and flow digram of working is attached in main branch 
  
  paramaeter for algorithum as follows
  Threshold value is 80 percent ,if it cross the 80 percent value ,the   object would be  detected and flag will be raised ,where is the algorithm is 80 percentage accurate 
  Where detected object has to be classified into biodegradable and non-biodegradable waste based on the list, we created so next we implement this using two list, then we import recycle name into file to particular director to classify the detected object 
For viewing the segregation work we deployed a method and called a function, which is nothing but representing the flag 0 and flag 1. where flag 1 denotes its biodegradable and similarly fashion the opposite flag 0 represent non-biodegradable


After detecting the object we store the scanned object count and segragaton count in thing speak cloud using API keys-‘NJM6WXH3J936SEZU’
We to push the scanned object into right spot into red bins and green bins  usinfg servo motor sg90 . By rotating into  0  degree we push the  biodegradable object into green bin and similarly we by rotating into  90  degree we push the  non-biodegradable object into red bin
  
