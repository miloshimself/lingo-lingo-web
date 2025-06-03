# LingoLingo Web

**LingoLingo** is a web-based language learning game developed as a team project at the School of Electrical Engineering, University of Belgrade. The application supports multiple languages and user roles, aiming to make language acquisition engaging through gamification.

## Features

- **Multilingual Support**: Practice and learn various languages.
- **User Roles**: Differentiate access and functionalities for learners, instructors, and administrators.
- **Gamified Learning**: Interactive challenges and quizzes to enhance vocabulary and grammar skills.
- **Progress Tracking**: Monitor learning progress over time.
- **Responsive Design**: Accessible on desktops, tablets, and mobile devices.

## Tech Stack

- **Frontend**: Vue.js
- **Backend**: PHP
- **Database**: MySQL
- **Styling**: CSS3
- **Version Control**: Git

## Getting Started

### Prerequisites

- PHP 7.4 or higher
- Composer
- Node.js and npm
- MySQL
- Git

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/miloshimself/lingo-lingo-web.git
   cd lingo-lingo-web
   ```

2. **Set up the backend**:

   - Install PHP dependencies:

     ```bash
     composer install
     ```

   - Configure the `.env` file with your database credentials.

   - Run migrations to set up the database schema:

     ```bash
     php artisan migrate
     ```

3. **Set up the frontend**:

   - Navigate to the frontend directory:

     ```bash
     cd frontend
     ```

   - Install Node.js dependencies:

     ```bash
     npm install
     ```

   - Build the frontend assets:

     ```bash
     npm run build
     ```

4. **Start the development server**:

   ```bash
   php artisan serve
   ```

   The application will be accessible at `http://localhost:8000`.