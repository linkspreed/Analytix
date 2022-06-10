# Analytix
Analytix💙 - as a developer,👨‍💻 get deep insights and analyzes for your websites📈 - free of charge, unlimited storage space and in real time


<div align="center">
	<img src="https://cdn.jsdelivr.net/gh/holic-x/holic-x/assets/github-contribution-grid-snake.svg" />
</div>

# <img align="left" alt="Twitter" width="30px" src="https://analytix.tk/uploads/brand/ys17CmIE61mY5SrzlKBu2UbanlIvzwW2l7qmb9PX.png" draggable="false" /> Analytix ([Click to try 🚀](https://analytix.tk/))

Bulit PHP **_Twitter Clone_** IN OOP style and using MYSQL Database. AJAX and Jquery for requests without reloading like Follow/unfollow, like, Search users, Show popups like comment , User lists, etc.


## Features

- Sign in / Sign UP
- Post Image or Normal Tweet.
- Retweet or Qoute Tweet (You can qoute the qouted tweet).
- Like Tweet.
- Add Comment and reply to the comment (Nested Comments).
- Mention User in Tweet or add hashtag to your tweet.
- Follow/Unfollow user.
- Get Notification when any previous action happened.
- Change Username/Password/Email From Settings.
- Search users by name and username.
- Edit Profile Like: (Change :avatar/username/cover etc).

## Running locally
 
 - Create New Database then import twitter.sql file on it.
 - go to PATH **core/classes/connection.php** and add your database info.

 ```php
    protected static $servername = "localhost";
    protected static $db_name="twitter";
    protected static $username = "root";
    protected static $password = "";
```
 then the project is ready to run in localhost!

## 📷 UI


### Index
![Index](screenshots/Index.png)

### Home
![Home](screenshots/Home.png)

### Tweet and Comments
![Post](screenshots/Inner-Post.png)

### Profile
![Profile](screenshots/Profile.png)

### Notifications
![Movie](screenshots/Notifications.png)

### Edit Account
![Edit](screenshots/Edit.png)

### Preview Image before Tweet
![Post](screenshots/Post.png)

### Users List (For following/likedby etc)
![Users](screenshots/Users.png)

### Setting
![Setting](screenshots/Setting.png) 
