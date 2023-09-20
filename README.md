# hackathon

This repository contains 2 main types of files:

Please run the app on an Android phone or emulator using the provided APK if you wish a complete view of the fully fledged application

1. The APK file for the Android application that was developed by the team
   
2. Files of the Dart code used in FlutteFlow to develop the application, be aware that we have only included the files corresponding to the main functions in order to facilitate the process of reading over the         code. The files in the repository are as follows, each file corresponds to functions on a page of the app:

   1. Statistics functions: This page displays statistics comparing the cost and time of sharing a ride x ordering one by yourself. This file contains the functions        to calculate statistics for the trips.The functions economia, tempo and economiamensal, in that order, calculate: percentage saved on each trip by sharing a          ride,    increase in time by sharing a ride and money saved after 30 days of sharing a ride instead of ordering one by yourself. Please be reminded that we are       considering    that it takes 10min and costs 5 dollars to move     by one cell. All calculations take into consideration the most efficient route that is able        to pick up both       riders and after that leave them at their destinations. This route is calculated by the function rota4pontos.]
      
   2. Create route: This page allows you to add your route to the database of the app, and sorts through it in order to find which one of the other routes added to         the database is the best for you to share a ride with. This is determined by the function rotasamigas
