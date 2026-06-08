# Assignment 4: Deploy Your First Web App using GitHub & Render

## Student Information

Name: Dechen Dorji
Student ID: 02250348 
Course: DSO101 - Continuous Integration and Continuous Deployment 


## Live Deployment
🔗 Live App: https://a4-simple-webapp.onrender.com

## GitHub Repository
🔗 Repo: https://github.com/deedox605/A4-simple-webapp.git



## Project Overview
This is a simple static HTML/CSS web application deployed automatically using a CI/CD pipeline with GitHub Actions and Render.com.

### Features
- Modern, responsive design with gradient background
- CI/CD pipeline with GitHub Actions
- Auto-deployment on every git push
- Mobile-friendly layout
- Interactive button with JavaScript


## Steps Taken

### Step 1: Create Simple Web App
Created an `index.html` file with:
- HTML5 structure
- CSS for styling (gradient background, animations)
- JavaScript for interactivity (button click, dynamic date)

## Screenshots
GitHub Repository
![repo.png](<Screenshot 2026-06-08 121053.png>)

GitHub Actions Workflow
![action.png](<Screenshot 2026-06-08 121114.png>)

Render Deployment
![render.png](<Screenshot 2026-06-08 121133.png>)

Live Website
![live.png](<Screenshot 2026-06-08 121152.png>)


## CI/CD Pipeline Flow
Push Code → GitHub → GitHub Actions → Render → Live Website
     ↓           ↓              ↓           ↓
   git push   triggers    runs workflow   auto-deploys


# Challenges Faced 

Git branch naming (master vs main)
Remote origin not found	
Render build path

## Project Structure
A4-simple-webapp/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── index.html
└── README.md

## Conclusion
Successfully created a complete CI/CD pipeline using GitHub Actions and Render.com. Every code push to the main branch automatically deploys the website, demonstrating a fully automated DevOps workflow.