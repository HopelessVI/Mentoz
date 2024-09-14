# Mentoz

**Mentoz** is a modern, AI-powered mentorship platform designed to create meaningful connections between mentors and mentees. It offers personalized learning experiences, gamified learning paths, and long-term mentorship programs tailored to individual needs. The platform leverages advanced tools for effective mentor-mentee collaboration and focuses on project-based mentorship.

## Features

- **AI-Powered Mentor Matching**: Uses machine learning algorithms to match mentees with the most suitable mentors based on skills, goals, and interests.
- **Gamified Learning Paths**: Provides interactive, engaging learning paths to encourage progress through challenges and rewards.
- **Long-Term Mentorship Programs**: Supports long-term mentorships with consistent goals and tracking, ensuring meaningful career or personal development.
- **Personalized Roadmaps**: Tailored learning and career roadmaps for each mentee, customized by mentors and enhanced through AI suggestions.
- **Mentor-Mentee Collaboration Tools**: In-app communication tools, file sharing, and progress tracking to streamline the mentorship process.
- **Project-Based Mentorship**: Focuses on hands-on, project-based learning experiences for mentees to build their skills with real-world applications.
- **Session Booking**: Integrated with **Calendly** for seamless mentor-mentee session scheduling.
- **Lexis Integration**: Generates transcripts for mentorship sessions using **Lexis**, allowing participants to focus on discussions without worrying about note-taking.

## Tech Stack

- **Frontend**: 
  - React
  - TypeScript
  - Tailwind CSS

- **Backend**:
  - Node.js
  - MongoDB
  
- **Third-Party Integrations**:
  - **Lexis**: For generating session transcripts.
  - **Calendly**: For session scheduling and management.

## Installation

To get the Mentoz project up and running on your local machine, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/HopelessVI/Mentoz.git
    cd Mentoz
    ```

2. **Install dependencies**:

    - Navigate to both the `client` and `server` directories and run the following:

    ```bash
    # Client
    cd client
    npm install
    
    # Server
    cd ../server
    npm install
    ```

3. **Set up environment variables**:

    Create a `.env` file in the `server` directory and configure the following variables:

    ```bash
    MONGODB_URI=<your-mongodb-connection-string>
    LEXIS_API_KEY=<your-lexis-api-key>
    CALENDLY_API_KEY=<your-calendly-api-key>
    ```

4. **Run the development servers**:

    - In the `client` folder, start the React app:

    ```bash
    npm run start
    ```

    - In the `server` folder, start the Node.js server:

    ```bash
    npm run dev
    ```

5. **Access the app**:

    Open your browser and go to `http://localhost:3000` to start using Mentoz.

## Project Structure

The project follows a clear separation of concerns between the frontend and backend.

- **client/**: Contains the React frontend with components, pages, and styles (using Tailwind CSS).
- **server/**: Houses the backend API, developed using Node.js and MongoDB.
- **models/**: Contains Mongoose models for MongoDB schemas.
- **routes/**: Handles API endpoints for various features, including mentorship programs, user management, and transcript generation.
- **services/**: Contains services for integrating external tools like Lexis and Calendly.

## Key Components

1. **Mentor Matching**: Utilizes AI models to dynamically pair mentees with mentors.
2. **Gamified Learning Paths**: Integrated with the learning management system to create progress tracking, challenges, and rewards.
3. **Collaboration Tools**: In-app messaging and file-sharing features.
4. **Transcript Generation**: Uses Lexis API for creating transcripts of mentorship sessions.
5. **Session Booking**: Managed through Calendly, allowing seamless session management between mentors and mentees.

## Contributing

Contributions are welcome! If you want to improve the platform, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request.

## Issues

If you encounter any issues or have suggestions, please open an [issue](https://github.com/YourUsername/Mentoz/issues) on the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or further information, please reach out via:

- GitHub: [Partha02Bh](https://github.com/Partha02Bh)
- Email: [Partha02Bh](gkp5625@gmail.com)

---

**Mentoz**: Empowering mentorship through AI and collaboration.
