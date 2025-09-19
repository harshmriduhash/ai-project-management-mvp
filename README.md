# ai-project-management-mvp
Backend and frontend for the MVP of the AI-driven project management tool
# AI Project Management MVP

# AI Project Management MVPs

A full-stack MVP for an AI-driven project management tool.  
Features include task tracking, deadline warnings, recommendations, user authentication, and testimonial management.

## Project Structure

```
.
├── backend/      # Express.js API server (PostgreSQL)
├── frontend/     # React.js client app
├── .env.example  # Example environment variables
├── package.json  # Root scripts for running both apps
```

## Features

- **Task Management:** Create, view, and prioritize tasks with deadlines.
- **Deadline Warnings:** Get alerts for tasks nearing their deadlines.
- **Recommendations:** Receive deadline extension suggestions for upcoming tasks.
- **Authentication:** Signup and login with JWT-based authentication.
- **Testimonials:** Submit and approve user testimonials (admin dashboard).

## Getting Started

### Prerequisites

- Node.js & npm
- PostgreSQL database

### Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/ai-project-management-mvp.git
   cd ai-project-management-mvp
   ```

2. **Configure environment variables:**
   - Copy `.env.example` to `.env` and fill in your PostgreSQL credentials.

3. **Install dependencies:**
   ```sh
   npm install
   cd backend && npm install
   cd ../frontend && npm install
   ```

4. **Set up the database:**
   - Create a PostgreSQL database and tables as needed for users, tasks, and testimonials.

5. **Run the app:**
   ```sh
   npm start
   ```
   - This will start both backend (`localhost:5000`) and frontend (`localhost:3000`) servers concurrently.

## Usage

- Access the frontend at [http://localhost:3000](http://localhost:3000)
- API endpoints are served from [http://localhost:5000](http://localhost:5000)

## Scripts

- `npm start` — Starts both backend and frontend
- `npm run start:backend` — Starts backend only
- `npm run start:frontend` — Starts frontend only

## Technologies

- **Frontend:** React, Axios, React Router
- **Backend:** Express, PostgreSQL, JWT, bcryptjs
- **Styling:** CSS modules

## License

MIT

---

For questions or contributions, please open an issue or pull request!