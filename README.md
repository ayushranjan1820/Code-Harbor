# Code-Harbor
This project is a Github-like application built on the MERN (MongoDB, Express.js, React.js, Node.js) stack, enhanced with TailwindCSS for styling and incorporating Github API for fetching user profiles and repositories. The core feature of this application is the implementation of social authentication using Passport.js, specifically tailored for Github authentication.

Features
• Authentication & Authorization with Passport.js (Github Auth): Users can sign in/sign up using their Github accounts, providing a seamless and secure authentication process.
• Fetch Github User Profiles and Repos: Once authenticated, users can fetch their Github user profiles along with repositories, mimicking the behavior of the actual Github platform.
• Filter Repos on the Client: Users have the ability to filter repositories based on various parameters, enhancing user experience and accessibility.
• Learn behind the scenes for authentication: The application provides insights into the authentication process, allowing developers to understand the mechanisms behind social authentication using Passport.js.
• Error Handling: Comprehensive error handling is implemented both on the server and client sides, ensuring smooth user experience and robustness of the application.
• Deployment on Render: At the end of the development cycle, the application can be easily deployed on Render, providing a hassle-free deployment process.

Tech Stack
• Frontend: React.js, TailwindCSS
• Backend: Node.js, Express.js
• Database: MongoDB
• Authentication: Passport.js (Github Auth)
• API Integration: Github API
• Deployment: Render

Setup .env file
PORT=5000
MONGO_URI=
GITHUB_API_KEY=
GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=
CLIENT_BASE_URL=

How to Run
1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Create a `.env` file based on the provided `.env.example` and fill in the required environment variables.
5. Run the development server using `npm run dev`.
6. Access the application in your web browser at the specified port.

Build the app
`npm run build`

Start the app
`npm start`

Contributing
• Contributions are welcome! Feel free to submit pull requests or open issues for any bugs or feature requests.
