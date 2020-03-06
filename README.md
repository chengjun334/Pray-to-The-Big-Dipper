# Pray-to-The-Big-Dipper

## Summary

Pray to the Big Dipper is a unique type of prayer in Taoism. Taoists believe that praying to the Big Dipper, is in charge of death at the right time, can avoid disaster and prolong life. This work will be an installation that informs people when do they can pray to the Big Dipper and which star are they parying to. People born in different zodiac years need to pray to different stars.

Example: In the Romance of the Three Kingdoms, Zhuge Liang tried to pray to The Big Dipper to extend life
https://www.youtube.com/watch?v=FiYysvyk3gc


## Inspiration 

-App 1, Hit The Wooden Fish

 ![image](https://github.com/chengjun334/Pray-to-The-Big-Dipper/blob/master/WoodenFish.jpg)

-App 2, Click To Pray is the official app of the Pope's Worldwide Prayer Network (Apostleship of Prayer)

 ![image](https://github.com/chengjun334/Pray-to-The-Big-Dipper/blob/master/ClickToPray.jpg)

## Physical Parts / Components


-Arduino


-Capacitive Sensor

 ![image](https://github.com/chengjun334/Pray-to-The-Big-Dipper/blob/master/weightSensor.jpg)


-Floor Cushion


-Rotary Encoder


-Laser Diode

 ![image](https://github.com/chengjun334/Pray-to-The-Big-Dipper/blob/master/laserDiode.jpg)

 -RGB Ring
 
  ![image](https://github.com/chengjun334/Pray-to-The-Big-Dipper/blob/master/rgbRingLight.jpg)
 
## Deconstruction System Diagram

| Data | Render | Simulation | Events |
| ------------- | ------------- | ------------- | ------------- |
| Today's date  | Lights on(if it's time to pray)  | / | Choose zodiac/born year  |
| kowtow times | Lights off(after 9 times kowtow)  | / | /  |

| Addition Features | Data | Render | Simulation | 
| ------------- | ------------- | ------------- | ------------- |
| 1 | Is anyone on the mat | (Not sure) Send an ir signal to display the star's picture on the screen | Image fades away after standing up  |

## Difficulty 

-Automatically time update (Keep time accurate)

-Position The Big Dipper (make sure the prayer is facing the right direction)

-The completeness and accuracy of the ceremony


## Storyboard

Overview
![image](https://github.com/chengjun334/Pray-to-The-Big-Dipper/blob/master/1.jpg)
 
Lights On (Inform you it is time to pray)
![image](https://github.com/chengjun334/Pray-to-The-Big-Dipper/blob/master/2.jpg)
 
When the cushion is under pressure, the Big Dipper will be projected
![image](https://github.com/chengjun334/Pray-to-The-Big-Dipper/blob/master/3.jpg)
 
After 9 times kowtows, Lights off
![image](https://github.com/chengjun334/Pray-to-The-Big-Dipper/blob/master/4.jpg)

## Timeline

|  Weeks | Events |
| ------------- | ------------- |
| Week3 | Proposal |
| Week4 | Research |
| Week5 | Research/Looking for Hardware |
| Week6 | Proof of Concept |
| Week7 | Booking Hardware |
| Week8 | Workshop |
| Week9 | Break |
| Week10 | Finish the base |
| Week11 | Prototype |
| Week12 | Workshop |
| Week13 | Workshop |
| Week14 | Finals Critique&Feedback |
| Week15 | Ready to Present/Finishing |
| Week16 | Present at show |
