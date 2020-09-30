# NewsSwipe
An Android-based News Swipe App
## Introduction
NewsSwipe is an interactive news app based on the MVVM Pattern, a Google Component Architecture. Users can either swipe or click to (dis)like news on the homepage. We also provide search page to search news by keywords. Moverover, users can recheck news and their details they stared before.

## Technologies
- Android Studio
- MVVM pattern
- JetPack
- Retrofit 
- Room Database
- RESTful
- Mindorks’s PlaceHolderView
- LiveData & ViewModel

## Launch
1. Copy this code repo to your local device.
2. Open Eclipse (or any other suitable IDE you frequently used), import this project as 'existed maven project'.
3. Before you want to run this project, fill your own Amazon RDS endpoint and password in the 'ApplicationConfig' file under src/main/java package.
4. Right click on 'pom.xml' file and choose run as 'Maven Install'.
5. After you see 'Build Success' in console, right click the project folder and choose 'Run on Server'. (Make sure you have installed Tomcat Server on your IDE already, detailed [here](https://crunchify.com/step-by-step-guide-to-setup-and-install-apache-tomcat-server-in-eclipse-development-environment-ide/)).
6. All set. Now you can see JobPlus run on your localhost. 

## Demo vedio
Here is a demo video for NewsSwipe, youtube link [here](https://youtu.be/4wKgVrIKnTo).
