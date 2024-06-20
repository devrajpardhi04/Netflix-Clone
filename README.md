
# Netflic Clone Project 🎬

This project is a Netflix clone, a full-stack web application that mimics the core functionalities of Netflix, including user authentication, browsing movies, and viewing detailed movie information. It uses modern web technologies to deliver a seamless user experience.

## Features ✨


- User authentication with Firebase
- Browse and search movies
- View detailed information about movies
- Responsive design with Styled-Components

## Technologies Used

- **Frontend:** React, Redux, React Router, Styled-Components
- **Backend:** Firebase
- **Others:** Axios for API requests, React Icons for icons

## Getting Started 🚀

Follow these instructions to set up the project locally.

### Installation

1. Clone the repository
   `git clone https://github.com/your-username/netflix-clone.git`

2. Navigate to the project directory
   `cd netflix-clone`

3. Install dependencies:
   ```bash
   npm install

   ```

4. Create a `.env` file in the server directory and add your MongoDB URI and Stripe API keys
   ```
  REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
   ```

5. Start the development servers
   ```
     npm start
   ```
6. Build for production:
```
    npm run build

  ```



## Usage
- **Home Page:** Browse the latest movies and TV shows.
- **Search:** Find movies by title.
- **Movie Details:** View detailed information about each movie, including synopsis and rating.
- **User Authentication:** Register and log in using Firebase authentication.

Project Structure:
netflix-clone/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   ├── App.js
│   ├── index.js
│   └── ...
├── .env
├── .gitignore
├── package.json
├── README.md
└── ...

