# NEU Library Visitor App

The **NEU Library Visitor App** is a web-based application designed to manage visitor check-ins for the NEU Library. Visitors can log in with their NEU email, select their college, role, and purpose of visit. Admins can view visitor statistics and detailed logs through a protected dashboard.

## Features

- Visitor login & check-in
- Role-based input (Student, Faculty, Staff, Visitor)
- Purpose of visit selection
- Real-time tracking of visits
- Admin dashboard with:
  - Total visits
  - Filtered visits by college, reason, and role
  - Detailed visitor logs
- Secure admin access (only allowed emails can access the dashboard)

## Admin Access

Only the following admin emails can log in to the admin dashboard:

- `admin1@neu.edu.ph`
- `jcesperanza@neu.edu.ph`

All other users are restricted.

## Live Demo

You can try the app live here:  
[NEU Library Visitor App](https://neu-library-visitor.web.app)

## Technologies Used

- **Firebase**: Authentication & Firestore database
- **HTML, CSS, JavaScript**: Frontend
- **GitHub**: Version control

## Deployment

The project is deployed via **Firebase Hosting**. All updates are automatically reflected at the live URL above when pushed to Firebase.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/alliencarllauzon-eng/neu-library-visitor.git
