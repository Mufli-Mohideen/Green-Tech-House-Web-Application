<div align="center">
  
# Green-Tech House Web Application
</div>

<div align="center">
  <img src="https://drive.google.com/uc?id=1EU4a1zOL0iWSvZKWpr7gRlracR-YOBMK" alt="GreenTech House Logo / Mufli-Mohideen" style="width:300px; height:auto">
</div>

Welcome to the Green-Tech House web application repository. This application is designed to provide a user-friendly interface for monitoring and controlling environmental conditions in greenhouses, leveraging HTML, CSS, JavaScript, and Firebase for real-time data management.

## Features

- **Real-Time Monitoring**: Monitor environmental parameters such as temperature, humidity, and light intensity.
- **Dynamic Control**: Control devices like fans, lights, and irrigation systems based on sensor data.
- **Data Visualization**: Visualize sensor data trends over time for better decision-making.
- **User Authentication**: Secure login and authentication using Firebase Authentication.
- **Database Management**: Store and retrieve sensor data in real-time using Firebase Firestore.

## Getting Started

Follow these instructions to set up and run the Green-Tech House web application on your local machine.

### Prerequisites

- Web browser (Chrome, Firefox, Safari, etc.)
- Text editor or integrated development environment (IDE) like Visual Studio Code, Sublime Text, or Atom.
- Firebase Account: Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).

### Installation

1. **Clone the Repository**
   ```sh
   git clone https://github.com/Mufli-Mohideen/Green-Tech-House-Web-Application.git
   cd green-tech-house-web

2. **Set Up Firebase**

   #### Create a Firebase Project

   - Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.

   #### Add Firebase to Your Web App

   - After creating your Firebase project, add a web app to your Firebase project:
     - Copy the Firebase configuration snippet provided.
     - Create a file named `firebaseConfig.js` in the root directory of your project.
     - Paste your Firebase configuration into `firebaseConfig.js`:

       ```javascript
       // firebaseConfig.js
       const firebaseConfig = {
         apiKey: "YOUR_API_KEY",
         authDomain: "YOUR_AUTH_DOMAIN",
         projectId: "YOUR_PROJECT_ID",
         storageBucket: "YOUR_STORAGE_BUCKET",
         messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
         appId: "YOUR_APP_ID"
       };

       // Initialize Firebase
       firebase.initializeApp(firebaseConfig);
       const db = firebase.firestore();
       ```

     - Replace `YOUR_API_KEY`, `YOUR_AUTH_DOMAIN`, `YOUR_PROJECT_ID`, `YOUR_STORAGE_BUCKET`, `YOUR_MESSAGING_SENDER_ID`, and `YOUR_APP_ID` with your actual Firebase configuration details.

   #### Configure Firebase in Your Web App

   - Ensure your `index.html` includes the Firebase JavaScript SDK:
   
     ```html
     <!-- index.html -->
     <script src="https://www.gstatic.com/firebasejs/9.1.3/firebase-app.js"></script>
     <script src="https://www.gstatic.com/firebasejs/9.1.3/firebase-firestore.js"></script>
     <script src="firebaseConfig.js"></script>
     ```

3. **Run the Application**

- Open `index.html` in your web browser locally or deploy the application on a web server.

## Contributing

If you want to contribute to this project, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

---

<div align="center">

## Developed by Mufli-Mohideen

</div>
