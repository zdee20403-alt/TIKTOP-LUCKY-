# TIKTOP-LUCKY-
Watch videos, earn points and spin rewards
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyAyK2ENmsEyQDuQYSi34bcmEIogT2cw9tc",
  authDomain: "watchandspin-16949.firebaseapp.com",
  projectId: "watchandspin-16949",
  storageBucket: "watchandspin-16949.firebasestorage.app",
  messagingSenderId: "958131507105",
  appId: "1:958131507105:web:d1af6626d000955e9285e0",
  measurementId: "G-C1RNNJ3Y0H"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
