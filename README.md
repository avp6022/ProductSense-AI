// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyDwIvwr9touNrtH3ghIIVJJ6EHz0JJFoFU",
  authDomain: "mayhem-2aeb0.firebaseapp.com",
  projectId: "mayhem-2aeb0",
  storageBucket: "mayhem-2aeb0.appspot.com",
  messagingSenderId: "7517278802",
  appId: "1:7517278802:web:06caf4b9deb7e41f4e458b",
  measurementId: "G-G6Y73NZV4S"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);