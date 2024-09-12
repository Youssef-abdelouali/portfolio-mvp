# Youssef's Personal Portfolio - MVP

## Overview
This project is a personal portfolio website showcasing my skills, projects, and experience as a software developer. The goal is to create a simple and visually appealing interface where users can explore my work, view my skills, and get in touch through a contact form.

## Technologies
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python with Flask
- **Database**: MySQL (Stores project data, skills, testimonials, and contact messages)
- **Version Control**: Git & GitHub

## Architecture
The project is divided into three main components:

1. **Client Side**
   - **Technologies**: HTML, CSS (for styling), JavaScript (for interactivity).
   - **Purpose**: To display portfolio items, allow users to navigate through pages, and submit the contact form.

2. **Server Side**
   - **Technology**: Python with Flask.
   - **Purpose**: Handle API requests to fetch data (projects, skills, testimonials) and process the contact form.

3. **Database**
   - **Technology**: MySQL.
   - **Purpose**: Store data about projects, skills, testimonials, and contact messages.

## Features

### API Routes:
- **/api/projects**
  - `GET`: Fetches all the projects to display on the portfolio.
  
- **/api/skills**
  - `GET`: Retrieves the list of skills to display.

- **/api/testimonials**
  - `GET`: Fetches testimonials from satisfied clients or colleagues.

- **/api/contact**
  - `POST`: Submits the contact form data and sends it to an email service.

## User Stories
1. As a visitor, I want to view the list of projects to see Youssef's previous work.
2. As a visitor, I want to navigate between sections (skills, projects, contact) to explore Youssef's expertise.
3. As an employer, I want to download Youssef's resume for offline review.
4. As a visitor, I want to submit a contact form to reach out directly to Youssef.

## Installation and Setup

### Requirements
- Python 3.8+
- Flask
- MySQL

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/Youssef-abdelouali/portfolio-mvp.git
