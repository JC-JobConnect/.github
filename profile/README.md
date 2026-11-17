# 💼 JobConnect – Job Portal Web Application

A full-stack job portal application designed to connect job seekers with employers. JobConnect allows users to explore job opportunities, search and filter jobs, discover companies, and access relevant job information through an intuitive interface.

## 📌 Project Overview

JobConnect is a web-based job portal developed as a collaborative team project. The application aims to simplify the job-searching process by providing a centralized platform where job seekers can explore available vacancies and companies.

The project uses React for the frontend, Django REST Framework for backend API development, and PostgreSQL for database management.

## ✨ Key Features

- **Job Listings:** Browse available job opportunities.
- **Job Search:** Search jobs by title, company, or description.
- **Job Filtering:** Filter jobs by category, location, job type, experience level, and work mode.
- **Company Directory:** Explore registered companies and their information.
- **Company Details:** View company profiles and associated job vacancies.
- **Job Details:** View detailed job descriptions, requirements, responsibilities, and salary information.
- **Related Jobs:** Discover other job opportunities within the same category.
- **User Authentication:** Secure authentication using JWT.
- **Responsive Interface:** User-friendly interface for different screen sizes.

## 🛠️ Technologies Used

### Frontend

- React.js
- JavaScript
- Axios
- React Router DOM
- React Icons
- Tailwind CSS

### Backend

- Python
- Django
- Django REST Framework
- Simple JWT
- django-filter

### Database

- PostgreSQL

### Development & Collaboration Tools

- Git
- GitHub
- Visual Studio Code
- Postman

## 📂 Project Structure

```text
JobConnect/
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── Components/
│       ├── Pages/
│       ├── Services/
│       └── App.jsx
│
├── backend/
│   ├── config/
│   ├── job/
    ├── authentication/
│   ├── manage.py
│   ├── requirements.txt
│   └── .env
│
├── README.md
└── .gitignore
```

## ⚙️ Installation & Setup

Follow these instructions to run JobConnect locally.

### Prerequisites

Make sure you have installed:

- Python 3.x
- Node.js and npm
- PostgreSQL
- Git

## 🔗 Project Repositories

| Component | Technology  | Repository                                                                  |
| --------- | ----------- | --------------------------------------------------------------------------- |
| Frontend  | React, Vite | [Frontend Repository](https://github.com/JC-JobConnect/JobConnect_frontend) |
| Backend   | Django, DRF | [Backend Repository](https://github.com/JC-JobConnect/jobconnect_api)       |

### 1. Clone the Repository

```bash
git clone https://github.com/orgs/JC-JobConnect/repositories
```

```bash
cd JobConnect
```

### 2. Backend Setup

Create a virtual environment:

```bash
python3 -m venv venv
```

Activate the virtual environment on Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure your `.env` file with the required database credentials and Django settings.

Run database migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

Start the Django development server:

```bash
python manage.py runserver
```

Backend will run at:

`http://127.0.0.1:8000/`

### 3. Frontend Setup

Open another terminal and navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the React development server:

```bash
npm run dev
```

The frontend will run at the local development URL displayed in your terminal.

## 🔗 API Endpoints

The backend provides RESTful APIs for job listings, company information, and user authentication.

| Method | Endpoint              | Description               |
| ------ | --------------------- | ------------------------- |
| GET    | `/job/v1/jobs/`       | Retrieve job listings     |
| GET    | `/job/v1/jobs/<id>/`  | Retrieve a specific job   |
| GET    | `/job/v1/companies/`  | Retrieve company listings |
| POST   | `/api/token/`         | Obtain JWT tokens         |
| POST   | `/api/token/refresh/` | Refresh JWT tokens        |

## 🔄 Git Workflow & Team Collaboration

We used Git and GitHub for version control and collaborative development.

Our workflow included:

- Creating and managing Git branches.
- Working on individual features using separate branches.
- Committing changes with meaningful commit messages.
- Pushing local changes to GitHub.
- Integrating completed features into the main branch.
- Collaborating and resolving code conflicts.

Example Git commands:

```bash
# Clone the repository
git clone https://github.com/orgs/JC-JobConnect/repositories

# Check the current branch
git branch

# Create a new feature branch
git checkout -b feature/feature-name

# Stage changes
git add .

# Commit changes
git commit -m "Add feature description"

# Push the branch
git push origin feature/feature-name

# Switch to main
git checkout main

# Update main
git pull origin main
```

## 📸 Screenshots

<p align="center">
  <img src="../job_connect%20Project/screenshorts/login.png" alt="Login/Registration Page" width="800"><br>
  <em>Login/Registration Page</em>
</p>

<p align="center">
  <img src="../job_connect%20Project/screenshorts/home.png" alt="Home Page" width="800"><br>
  <em>Home Page</em>
</p>

<p align="center">
  <img src="../job_connect%20Project/screenshorts/joblist.png" alt="Jobs Listing Page" width="800"><br>
  <em>Jobs Listing Page</em>
</p>

<p align="center">
  <img src="../job_connect%20Project/screenshorts/job%20details.png" alt="Job Details Page" width="800"><br>
  <em>Job Details Page</em>
</p>

<p align="center">
  <img src="../job_connect%20Project/screenshorts/companies.png" alt="Companies Page" width="800"><br>
  <em>Companies Page</em>
</p>

<p align="center">
  <img src="../job_connect%20Project/screenshorts/myapplication.png" alt="My Applications Page" width="800"><br>
  <em>My Applications Page</em>
</p>

<p align="center">
  <img src="../job_connect%20Project/screenshorts/my%20profile.png" alt="My Profile Page" width="800"><br>
  <em>My Profile Page</em>
</p>

<p align="center">
  <img src="../job_connect%20Project/screenshorts/about.png" alt="About Us Page" width="800"><br>
  <em>About Us Page</em>
</p>

<p align="center">
  <img src="../job_connect%20Project/screenshorts/contact.png" alt="Contact Page" width="800"><br>
  <em>Contact Page</em>
</p>

## 👥 Team Members

This project was developed collaboratively by:

- Md Alamin
- Mahamudha Sultana
- Tripti Mondal
- Rubayet Prodhan

## 🚀 Future Improvements

- Job application submission system.
- User profile management.
- Resume upload functionality.
- Employer dashboard.
- Advanced job recommendation system.
- Email notifications for job opportunities.

## 📄 License

This project was developed for educational and learning purposes.
