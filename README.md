# Flask Portfolio Website

## Description
A personal portfolio website built using Flask to showcase profile, skills, and projects.  
This project demonstrates Flask routing, HTML templates, static files handling, and basic deployment setup.

---

## Features
- Home page with profile details
- About Me section
- Skills list
- Projects list
- Contact page
- Clean UI using HTML & CSS
- Flask backend routing

---

## Tech Stack
- Python
- Flask
- HTML
- CSS
- Gunicorn (for deployment)

---

## Project Structure

portfolio-flask/
│
├── app.py
├── requirements.txt
├── Procfile
│
├── templates/
│   ├── index.html
│   └── contact.html
│
├── static/
│   └── style.css

---

## How to Run Locally

1. Clone the repository

git clone https://github.com/your-username/portfolio-flask.git  
cd portfolio-flask

2. Install dependencies

pip install -r requirements.txt

3. Run the Flask app

python app.py

4. Open in browser

http://127.0.0.1:5000

---

## Deployment

This project is deployment-ready using Render with:
- Procfile
- gunicorn
- requirements.txt

Start Command used in deployment:

gunicorn app:app

---

## Learning Outcomes
- Understanding Flask routing
- Working with Jinja2 templates
- Static file management
- Structuring a Flask project
- Basic web app deployment

---

## Author
Uma Karthik  
Python Developer Intern
