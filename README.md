# AI StudyBuddy API

AI StudyBuddy is a RESTful backend built with Node.js, Express, MongoDB, Mongoose, JWT authentication, bcryptjs, and Google Gemini AI.

## Features

* User registration and login
* JWT authentication and role-based access
* Study material upload and management
* AI-generated summaries
* AI-generated flashcards
* AI-generated quizzes
* AI-generated study plans
* MVC architecture

## Getting Started

1. Copy `.env.example` to `.env`
2. Install dependencies:

```bash
npm install
```

3. Start the app:

```bash
npm start
```

## Environment Variables

* `PORT`
* `MONGO_URI`
* `JWT_SECRET`
* `GEMINI_API_KEY`

## API Endpoints

### Auth

* `POST /api/auth/register`
* `POST /api/auth/login`

### Study Materials

* `POST /api/material/upload`
* `POST /api/materials/:id/summarize`

### AI

* `POST /api/ai/flashcards`
* `POST /api/ai/quiz`
* `POST /api/ai/study-plan`

### Admin

* Admin APIs for user management and system operations

## Testing with Thunder Client

Use the above endpoints in **Thunder Client** or **Postman** with the required JSON or form-data payloads.

Example requests and responses can be tested using the API endpoints provided above.
