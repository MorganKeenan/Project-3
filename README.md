# Project-3

### WireFrames & Basic Ideation:

  <img src = "./wireframes/markerwireframe1.jpg" width="800" height="600">
  <img src = "./wireframes/markerwireframe2.jpg" width="800" height="600">
  <img src = "./wireframes/Ideation.jpg" width="800" height="600">
  <img src = "./wireframes/selectBus.png">
  <img src = "./wireframes/selectRoute.png">
  <img src = "./wireframes/selectStop.png">

### Trello Board

  https://trello.com/b/eBpW34QS/longhaul-app

### Heroku Link

  http://longhaul1.herokuapp.com

### Technologies Used

    #Back-End
    Node.js
    PostgreSQL
    Sequelize
    Express
    GTFS (Google Real Time Data Feed)
    Passport
    JSON Web Tokens
    Mocha
    Chai
    Jasmine
    Karma

    #Front-End
    Angular
    Ionic
    Sass
    Cordova
    HTML5/CSS3

### Research
  
    The idea for the project came from Brian's direct experience of riding the bus to downtown Denver from Northglenn. He wanted to turn that commute into more productive time, or perhaps a nap. Starting with the idea of an alarm clock based on real-time GPS data, we started looking at how to accomplish that. Luckily, Google provides data streams of real-time GPS locations on all the buses in the RTD sysem. They use the data in Google Maps, but they make it available. Much research and testing went into processing that datastream to make it useful. In addition, we looked into other apps that may do the same thing. There are several competitors providing apps designed to be used in-transit:
    
   Transit app - https://transitapp.com/.  Mainly useful for seeing when the next bus or train is departing. Not useful for when it arrives.
   
   RTD NextRide - https://www.rtd-denver.com/app/nextride . 
    Again, mainly useful for determining when a bus or train will arrive at the stop you are waiting at. Not useful for predicting arrival time. 
    
   Transit Tracker app - https://itunes.apple.com/us/app/transit-tracker-denver/id836324637?mt=8. 
   I can't even tell what this app is intending to do because the interface is mystifying. 
   
   Swiftly app https://play.google.com/store/apps/details?id=com.swyftapp.free&hl=en
   Some confusion as to whether it actually uses realtime data to show bus locations. Designed mainly to show best/cheapest/most efficient ways to travel, not just public transit. It works in several cities but doesn't work the same way in each city. No alarm function. 
    


