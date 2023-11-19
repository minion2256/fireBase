# fireBase
my intro to firestore firebase
creata a google account and create your  project using web app
 secondly  you are suppose to install http-server to  your machine  so as to avoid this error " from origin 'null' has been blocked by CORS policy"
 this means when not using http-server wont be able to send your file as 'file:// '
 http serve disables CORS 
 use npm install -g http-server if you have installed node.js
 # npm install -g http-server
 and then run http-server
 # http-server
 in the index page,
 # in  'import {firebase} from "http://127.0.0.1:8080/details.js'
 http://127.0.0.1:8080 is the address produce when run http-server, so incase you wont use the http://127.0.0.1:8080 address you can use the address produced and replace it in the
 import {firebase} from "http://127.0.0.1:8080/details.js' to your addres example import {firebase} from "http://127.0.0.1:9080/details.js'

# import {firebase} from "http://127.0.0.1:8080/details.js' to your addres example import {firebase} from "http://127.0.0.1:9080/details.js' 
the file details.js contains the firebase configuration credentials, so you can put your credentials  there 
# example 
  const firebaseConfig = {
    apiKey: 'YOUR_API_KEY',
    authDomain: 'YOUR_AUTH_DOMAIN',
    projectId: 'YOUR_PROJECT_ID',
    storageBucket: 'YOUR_STORAGE_BUCKET',
    messagingSenderId: 'YOUR_MESSAGING_SENDER_ID',
    appId: 'YOUR_APP_ID'
  };
  export  const firebase =firebaseConfig;

# wish you well 
 

 

