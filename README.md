# Node.js based app that is able to respond to emails sent to your Gmail mailbox while you’re out on a vacation. 

Description
-This app  is able to respond to emails sent to your Gmail mailbox while you’re out on a vacation.

 Features
- The app should check for new emails in a given Gmail ID
- The app should send replies to Emails that have no prior replies
- The app should add a Label to the email and move the email to the label
- The app should repeat this sequence of steps 1-3 in random intervals of 45 to 120 seconds

 Libraries  
-1.googleapis:This package is imported from the googleapis module and provides the necessary functionality to interact
   with various Google APIs, including the Gmail API.
-2.OAuth2:The OAuth2 class from the google.auth module is used to authenticate the application and obtain an access
   token for making requests to the Gmail API. It handles token refresh and retrying requests if necessary. 




# Install NPM dependencies
npm install

#Install googleapis and nodemon
npm install googleapis nodemon

# Then simply start your app
npm start
```

