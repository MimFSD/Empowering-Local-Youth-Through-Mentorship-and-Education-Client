# AidAlliance

AidAlliance is a web application designed to connect volunteers with organizations in need. Whether you are an organization looking for volunteers or an individual looking to lend a hand, AidAlliance provides a platform to facilitate these connections effectively.

![AidAlliance](https://i.ibb.co/PmpGsm2/360-F-272398712-z28-EMWLb-M9-Y8zojg51t-LZo4-D8-Ju3-R7-EG-1.jpg)

## Features

- **Dynamic Navbar**: Navigate easily with our dynamic navbar, featuring conditional login/logout buttons and a dropdown menu for easy access to your profile.
- **Footer**: Stay connected with our footer containing website information, copyright, contact details, and social media links.
- **404 Page**: Don't worry if you get lost, our 404 page will guide you back on track.
- **Authentication**: Secure login functionality with password and email-based authentication. Users can also log in using Google or GitHub.
- **Registration**: Simple and secure registration process with password verification.
- **Home Page**:
  - Eye-catching slider/banner with meaningful information.
  - Volunteer Needs Now section showcasing upcoming volunteer opportunities.
  - Additional relevant sections for more information.
- **Post Management**: Users can add, update, or delete volunteer need posts. They can also manage volunteer requests made by them.
- **Search and Layout Options**: Search functionality to find volunteer need posts by title and option to switch between card view and table view.
- **Server Integration**: Integrated with Firebase for authentication and Firestore for database management.
- **Responsive Design**: Fully responsive design using Tailwind CSS and optional Flowbite for styling.

## Demo

Explore the website [here](https://volunteer-e5e10.web.app/).

## Technologies Used

- React
- Firebase (Authentication, Firestore)
- Tailwind CSS
- Flowbite (Optional)


## Installation Steps

Ah, got it! You want to **run only the frontend (React) part of a MERN stack** but use **Firebase** instead of the backend server for things like authentication or database. Here’s how to do it step by step:

---

## 🔹 Steps to Run MERN Frontend with Firebase

### 1. Go to Your Frontend Folder

If your React frontend is in a separate folder (commonly `client`):

```bash
cd client
```

---

### 2. Install Dependencies

Make sure you have all frontend dependencies:

```bash
npm install
```

Install Firebase SDK if not already installed:

```bash
npm install firebase
```

---

### 3. Setup Firebase

1. Go to [Firebase Console](https://console.firebase.google.com/) and create a project.
2. Create a **Web App** in your project and copy the Firebase config:
3. Replace all backend calls (like REST API requests) with Firebase Auth, Firestore, or Realtime Database.

---

### 4. Run the Frontend

```bash
npm start
```

This will start the React app at:

```
http://localhost:3000
```

---

### 5. Optional: Connect to Firebase Auth/Firestore

* For **Authentication**, use `auth` from Firebase.
* For **Database**, use `db` from Firestore.
* Remove any server API calls if you want to run purely frontend with Firebase.

---

💡 **Tip:** You can host the React app on **Firebase Hosting** too:

```bash
npm install -g firebase-tools
firebase login
firebase init
firebase deploy
```



## Contributing

Contributions are welcome! Fork the repository and submit a pull request detailing your changes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

