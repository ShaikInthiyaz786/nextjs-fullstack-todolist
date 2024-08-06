# Next.js Todo Application
This is a full-stack Todo application built with Next.js, Firebase Authentication, and Firestore. The app allows users to create, edit, and delete tasks while ensuring secure user authentication.

## Features
User Authentication: Secure authentication using Firebase.
Todo Management: Add, update, and delete tasks.
Responsive Design: Mobile and desktop friendly.
Real-time Database: Tasks are stored in Firestore for real-time updates.
Tech Stack
Frontend: Next.js, React
Backend: Firebase Authentication, Firestore
Styling: Tailwind CSS
Installation
Clone the repository:

 
## Copy code
git clone https://github.com/ShaikInthiyaz786/nextjs-fullstack-todolist.git
Navigate to the project directory:

 
## Copy code
cd nextjs-todo-app
Install dependencies:

 
## Copy code
npm install
Create a .env.local file in the root directory and add your Firebase configuration:

## env
Copy code
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
Start the development server:

 
## Copy code
npm run dev
Open your browser and navigate to http://localhost:3000.

## Usage
Sign Up / Log In: Create a new account or log in with existing credentials.
Manage Todos: Add, edit, and delete tasks.
Logout: Securely log out from the application.
Deployment
To deploy the application, use Vercel or another platform of your choice:

 
## Copy code
vercel
Follow the deployment steps and your app will be live!