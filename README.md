# CI Demo Project

This repository is designed to demonstrate a Continuous Integration (CI) workflow using a simple Python application.  
It’s a practical showcase of setting up automated testing and pipeline automation.

---

##  Project Overview  
The goal of this project:  
- Build a small Python app (`app.py`) which performs a basic function (and has a test).  
- Set up CI (e.g., via GitHub Actions) to automatically run the tests on every commit/pull request.  
- Ensure fast feedback and create a reproducible development workflow.

---

##  Project Structure  
CI_demo_proj/
├── app.py # Main application logic
├── _test.py # Unit test(s) for the application
├── .github/workflows/ # CI pipeline definitions
│ └── <workflow-file>.yml # Workflow file(s)
├── .gitignore # Files/folders to ignore in git
└── README.md # This documentation

---

## Technologies Used

-Python – core application & test code.
-GitHub Actions – as CI engine (via .github/workflows).
-Git / GitHub – version control and collaboration.



