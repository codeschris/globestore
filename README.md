# GlobeStore

Welcome to GlobeStore! This repository contains the source code for the GlobeStore e-commerce platform, consisting of a Next.js frontend and a Django backend.

## Project Structure

- **storefront**: The frontend application built with Next.js 15 and React 19.
- **backend**: The backend API built with Django.

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [Python](https://www.python.org/) (v3.8 or higher)
- npm (usually comes with Node.js)

## Setup Instructions

### Backend Setup

1. **Navigate to the backend directory:**
   ```bash
   cd backend
   ```

2. **Create a virtual environment:**
   It's recommended to use a virtual environment to manage dependencies.
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment:**
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run migrations:**
   Apply database migrations to set up your database.
   ```bash
   python manage.py migrate
   ```

6. **Start the development server:**
   ```bash
   python manage.py runserver
   ```
   The backend server will typically run at `http://127.0.0.1:8000`.

### Storefront (Frontend) Setup

1. **Navigate to the storefront directory:**
   Open a new terminal window and navigate to the frontend folder.
   ```bash
   cd storefront
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **View the application:**
   Open your browser and visit [http://localhost:3000](http://localhost:3000).

## Contributing

Please make sure to run linting commands before pushing changes.

- **Frontend Linting**: `npm run lint` inside the `storefront` directory.