# WhereRU

WhereRU app lets people meet in a virtual room and share their locations with eachother **in realtime**.

This project is prepared for code challenge simulation for Re:Coded.

You are supposed to fork this repo and develop this incomplete WhereRU app considering the following requirements:

### Screens

The app has two screens: Login Screen and Map Screen. You can follow these designs when you are developing this app. However if you want to make some subtle changes you can do as you wish.

![login screen](https://user-images.githubusercontent.com/4990386/27486868-a5f3d93e-583a-11e7-808d-4621de7cc096.png)
![map screen](https://user-images.githubusercontent.com/4990386/27486869-a6122074-583a-11e7-9553-e47d1578071e.png)


#### Giriş Ekranı

This screen is the first screen users see when they open the app. After entering name and a room number and picking a color; users can navigate to the map screen. 

The background color and the button tint changes as the user picks a color.

You can find the colors used here:

RED: #F44336
PURPLE: #9C27B0
BLUE: #2196F3
GREEN: #4CAF50

#### Harita Ekranı

In this screen, the picked room is listened in real time and the location of the users also sent to the room. So if there are two people in the room 1234, they will see eachother's locations as long as this screen is open on both devices.

You can use the markers provided by Google Maps SDK, with different colors. When users change their locations, their markers are also moved in the map.

All of this realtime transaction is done via Firebase Realtime Database

### Firebase Database

The Firebase dependency is already added to the project.

Reference: `https://recoded-challenge.firebaseio.com/`
