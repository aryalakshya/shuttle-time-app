#  Shuttle Time - Badminton Court Booking App

A real-time, web-based application for booking badminton courts, built with React and powered by Firebase. This app allows users to view available time slots for the next day, book a spot for themselves or a group, and manage their upcoming bookings.

##  Features

* **User Authentication:** Secure sign-up, sign-in, and password reset functionality using Firebase Authentication.
* **Real-Time Slot Availability:** View court availability for tomorrow in real-time. Slots update instantly for all users when a booking or cancellation occurs.
* **Court Selection:** Easily switch between different courts to view their schedules.
* **Dynamic Booking:** Book one or more spots in an available time slot. The app prevents overbooking and enforces a daily limit of two slots per user.
* **Booking Management:** A personalized "My Bookings" page shows all upcoming bookings for today and tomorrow.
* **Cancellations:** Users can cancel their bookings for the next day, immediately freeing up the slot for others.
* **Live Notifications:** Receive in-app notifications when a previously booked slot becomes available.
* **Responsive Design:** A clean, dark-themed UI that works smoothly on both desktop and mobile devices.

##  Tech Stack

* **Frontend:** React (via CDN)
* **Styling:** Tailwind CSS
* **Backend & Database:** Firebase (Firestore, Authentication)
* **Development Server:** live-server

##  Local Setup and Installation

Follow these steps to get the project running on your local machine.

### 1. Prerequisites

* [Node.js](https://nodejs.org/) (which includes npm) installed on your computer.
* A Google account to create a Firebase project.

### 2. Clone the Repository

Clone this project to your local machine:
```bash
git clone https://github.com/aryalakshya/Shuttle-Time.git
cd Shuttle-Time
```

### 3. Set Up Firebase

This project requires a Firebase backend to handle authentication and the database.

1.  Go to the [Firebase Console](https://console.firebase.google.com/) and click **"Add project"**.
2.  Give your project a name (e.g., "shuttle-time-dev") and follow the on-screen instructions.
3.  Once your project is created, navigate to the **Project Settings** (click the gear icon ⚙️).
4.  Under the **General** tab, scroll down to "Your apps".
5.  Click the web icon **</>** to register a new web app.
6.  Give the app a nickname and click **"Register app"**.
7.  Firebase will provide you with a `firebaseConfig` object. **Copy these credentials.**

### 4. Install Dependencies and Run

1.  Install the necessary development dependencies (in this case, `live-server`):
    ```bash
    npm install
    ```
2.  Start the local development server:
    ```bash
    npm run dev
    ```
The application will automatically open in your default web browser.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
