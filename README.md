# AJ-Messenger-Project

This is a messenger app for Android based on Firebase (Cloud Firestore and Realtime Database) for live chat.

This app is suitable for enterprise messenger where all users appears because there is no management function such as add / delete / find friends.

### FEATURES ###
- 1:1 and Group chat
- Text Messaging
- Separate message Bubble color for sent and receive message.
- Realtime Database using FireBase

### INSTALLATION ###
1. Clone this source from github (in android studio).
2. Copy google-services.json to /app folder.

   You can get google-services.json from [Firebase Console](https://support.google.com/firebase/answer/7015592?hl=en)
   
   OR
   
   in android studio, you can make with Tool > Firebase menu 
  
3. Run.
  
   If you see a message like "Please select Android SDK", modify gradle file and run sync now.


4. To use push server(Google Cloud Messaging), you must put the key provided by Firebase in the request header(Authorization) in the sendGCM function in ChatActivity.java.

# Screenshots:
### Landing Page
<img src="https://github.com/amark720/AJ-Messenger-Project/blob/master/Screenshot1.png" alt="Landing Page" height="70%" width="100%">

### Sign Up Page
<img src="https://github.com/amark720/AJ-Messenger-Project/blob/master/Screenshot2.png" alt="Sign Up Page" height="70%" width="100%">

### Group Chatting Page
<img src="https://github.com/amark720/AJ-Messenger-Project/blob/master/Screenshot3.png" alt="Group Chatting Page" height="70%" width="100%">

## AJ Messenger Short Report
```FCM
https://github.com/amark720/AJ-Messenger-Project/blob/master/AJ%20Messenger%20report.pdf
```
