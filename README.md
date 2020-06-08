## Introduction

Collection of projects in the area of Data Science, Data Engineering, Automation, AI are presented on this page. The link to each associated github page is included and by clicking it, you will be led to the code of the respective project together with the detail description.

## [Truck's operational distance logger](https://github.com/hkbtotw/Android_AzureCS_BatchRead_v2)

**Why?**
In logistics, cost management is one of the key performance indicator which management needs to keep monitoring and optimizing to drive the business to success. Oftentime, the problem in acheiving this goal is inability to obtain high quality operational information and the truck's operational distance is one good example of such information that could impact the transportation cost directly. However, getting the covered traveling distance is not easy as most companies rely on driver to input this information on either paper form or online data entry application in which the data can be easily manipulted for any other kind of reasons but the benefits of the company.

**Solution:**
This application was developed to help increasing the quality of transportation data by trying to removing human factor from inputting data the system. 
In this application, the mile number shown in truck dashboard will be extracted by OCR and the data will be logged into the parse server for analyzing and other analytical activities. Additionally, it could help providing driver a feedback to each's daily operation with which driver could improve the driving behavior and plan to support the cost optimizaton and SLA goals.

**Technology**
- **Azure Cognitive Service**
- **Amazon EC2**  _Parse Server_
- **Google** Text recognition, Firebase ML, Google Drive and Map api
- **Android Application Development**
- **Computer Vision**
- **Tensorflow Object Detection API**
- **Image Processing**

[View application screen](https://github.com/hkbtotw/Android_AzureCS_BatchRead_v2/blob/master/screenCapture/Screen01.jpg)



## Truck driver's driving behavior monitoring

**Why?**
In logistics, delivery on-time is one of the major SLA which the business needs to fulfill this promise to their customers. Therefore, ability to track the status of each delivery and the driving behavior (e.g. speed ) of each truck driver is the leading indicator to this particular KPI.

**Solution:**
This application was developed as a protoytpe of the truck driver's driving behavior and delivery status monitoring.

### [Client : Android Application](https://github.com/hkbtotw/DriveBehavior)

**Technology**
- **Amazon EC2**  _Parse Server_
- **Google** Google Map api
- **Android Application Development**

[View application screen](https://github.com/hkbtotw/DriveBehavior/blob/master/ScreenCapture/ScreenPortrait.jpg)

### [Monitoring dashboard(desktop & web application)](https://github.com/hkbtotw/DriveBehavior_Monitoring)

**Technology**
- **Amazon EC2**  _Parse Server_
- **Python**

[View application screen](https://github.com/hkbtotw/DriveBehavior_Monitoring/blob/master/ScreenCapture.JPG)


## [Weather information message](https://github.com/hkbtotw/raspi-chatbot)

**Why?**
In Bangkok, one of cities with the worst traffic condition in the world, just a little bit of drizzle could make the traffic condition much worse. In the logistics business, the weather factor impacts their SLA directly as the flash flood on the street or worsen traffic condition from slowing down traveling speed of cars on the road will immediately contribute to the deliver on-time KPI of the business. 

**Solution:**
This application runs on LINE application platform. It works by using the submitted location to pull the weather data and return the information to the user together with the extracted tweets relating to hashtag #Traffic  #Accidents #Rain #Flood sorted by distances from the location of user. With this information, the user could use to plan out the trip so they could arrive at the destination on the route with no accidents or raining.

**Technology**
- **LINE** application development
- Openweather API
- **Heroku**
- **Twitter**
- **Chatbot** 
- **Python**
- **NLP**

[View application screen](https://github.com/hkbtotw/raspi-chatbot/blob/master/ScreenCapture_Weather.JPG)




## Contact
My personal email address is _hkbtotw@gmail.com_ . Feel free to contact me if you would like to know more about any projects posted on this page or an opportunity of collaborations.
