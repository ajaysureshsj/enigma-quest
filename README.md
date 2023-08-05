# Enigma Quest - Quiz Web App

Welcome to Enigma Quest, an open-source quiz web app that will challenge your mind with intriguing brain teasers and riddles! Test your problem-solving skills and enjoy the thrill of solving puzzles in this interactive and engaging quiz experience.

## Features

- **Randomized Questions**: Each time you visit the app, you will encounter a different set of brain teasers and riddles, keeping the quiz experience fresh and exciting.

- **Timer Challenge**: Feel the adrenaline rush as you race against the clock to solve each puzzle. The timer adds an extra layer of excitement to the quiz.

- **Scoring System**: Earn points for correct answers.

- **Responsive Design**: Enjoy a seamless quiz experience on desktops, tablets, and mobile phones.

## Technical Details

### Tech Stack

- Frontend: React (HTML, CSS, JavaScript)
- Backend: Node.js (Express.js for the server)

### API Used

- Open Trivia Database (OpenTDB) API: Provides many trivia questions across various categories and difficulty levels.

### Implementation Details

- The quiz questions are fetched from the OpenTDB API using Axios on the backend.
- The React frontend communicates with the Node.js server using API endpoints to retrieve random questions and submit answers.
- The server handles scoring logic and provides the following question to the frontend.
- A timer is implemented on the frontend using JavaScript to keep track of the time for each question.

## Resource Section

The following resources will aid you in building the Enigma Quest quiz web app:

- **Open Trivia Database (OpenTDB) Documentation**: The official Documentation of the OpenTDB API provides details on the available endpoints and how to use them to fetch trivia questions.

- **React Documentation**: Comprehensive Documentation for React, helping you learn about React components, state management, and UI design.

- **Node.js Documentation**: Detailed Documentation on Node.js and Express.js to help you understand how to set up the backend server and handle API requests.

- **Axios Documentation**: Axios is used for making HTTP requests in the backend. Its Documentation will guide you in integrating and using Axios in your project.

- **JavaScript Timer Implementation**: Resources on implementing a timer using JavaScript for the countdown feature during the quiz.

- **HTML/CSS Design Tutorials**: Various tutorials and resources on web design using HTML and CSS, ensuring a visually appealing UI for Enigma Quest.

## Getting Started

### Prerequisites

- Node.js installed on your machine.

### Installation

1. Clone the repository: `git clone https://github.com/your-username/enigma-quest.git`
2. Navigate to the project directory: `cd enigma-quest`
3. Install frontend dependencies: `cd frontend && npm install`
4. Install backend dependencies: `cd backend && npm install`
5. Start the frontend: `cd frontend && npm start`
6. Start the backend: `cd backend && npm start`

The frontend will run on `http://localhost:3000`, and the backend will run on `http://localhost:5000`.

## Deployment

To deploy Enigma Quest to a live server, follow these steps:

1. Build the frontend: `cd frontend && npm run build.`
2. Move the build files to the backend's public directory: `mv frontend/build backend/public.`
3. Deploy the backend to your hosting platform.

## Contributing

We welcome contributions from the open-source community to enhance the Enigma Quest quiz web app. Feel free to submit a pull request if you have new puzzle ideas, improvements to the UI, or bug fixes.

## License

Enigma Quest is released under the [GNU General Public License version 3 (GPL V3)](LICENSE).

## Acknowledgements

Special thanks to the Open Trivia Database (OpenTDB) for providing a vast collection of trivia questions and making Enigma Quest even more exciting.

## Contact

If you have any questions or suggestions, feel free to reach out to us via email at ajaysureshsjofcl@gmail.com

Get ready for a brain-twisting adventure with Enigma Quest! Happy quizzing! 🧠🔍
