<script>
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyDHFF8_AAlETxtA1tCPYEHMY3vY49HLs6Y",
  authDomain: "crypto-4c0d1.firebaseapp.com",
  databaseURL: "https://crypto-4c0d1-default-rtdb.europe-west1.firebasedatabase.app",
  projectId: "crypto-4c0d1",
  storageBucket: "crypto-4c0d1.appspot.com",
  messagingSenderId: "843949753998",
  appId: "1:843949753998:web:07fd9ff326d8d8247a6bdf",
  measurementId: "G-7B06BMMEHS"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);

firebase.initializeApp(firebaseConfig);
var test = document.getElementById("testing")

var dbRef = firebase.database().ref().child("text");
dbRef.on("value", snap => test.innerText = snap.val());

</script>
<template>
  <div class="about">
    <h1 id="testing"></h1>
  </div>
</template>