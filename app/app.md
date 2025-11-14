```

// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBHEsZZ4XSwb1wCnieTJ-bWDIp2i7vD-MA",
  authDomain: "elderly-care-app-d4fe9.firebaseapp.com",
  projectId: "elderly-care-app-d4fe9",
  storageBucket: "elderly-care-app-d4fe9.firebasestorage.app",
  messagingSenderId: "293510422834",
  appId: "1:293510422834:web:838fe304a832ea1e0af72b",
  measurementId: "G-N44RJ8BFJY"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);

```
