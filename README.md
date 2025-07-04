# CI/CD + TDD/BDD Final Project (by Vitaliia Palchei)

This project was completed as part of my **DevOps and QA Automation training**. It demonstrates my ability to work with **Test-Driven Development (TDD)**, **Behavior-Driven Development (BDD)**, and **CI/CD pipelines** using modern tools like Docker, GitHub Actions, and Tekton.

---

## What I Practiced and Contributed

✅ **Test Automation & QA**
- Worked with predefined unit and route tests in `test_models.py` and `test_routes.py`
- Practiced BDD by writing and updating Gherkin scenarios in `features/products.feature`
- Edited step definitions in `load_steps.py` and `web_steps.py`
- Triggered test execution through automated CI/CD workflows (not manual test runs)

✅ **CI/CD Pipelines**
- Set up and reviewed automated pipelines using GitHub Actions (`.github/workflows/workflow.yml`)
- Worked with Tekton tasks to run tests and build steps (`.tekton/tasks.yml`)
- Gained experience in integrating test steps into continuous delivery pipelines

✅ **Environment & Deployment**
- Containerized the application using Docker and managed app lifecycle with `Dockerfile`, `Makefile`, `Procfile`, and `.flaskenv`
- Used command-line tools and pre-built scripts to install dependencies (`setup.sh`)
- Configured runtime environments using `.env` templates and project settings

✅ **Challenges Overcome**
- I overcame my initial fear of using the terminal and automation tools, and learned to confidently run and verify CI/CD pipelines and modify test-related files in a structured development environment

---

## Tools & Technologies Used

- GitHub Actions, Tekton  
- Docker, Makefile, Git  
- BDD: Gherkin syntax (feature files + step definitions)  
- Flask application structure (Python backend)

---

## Folder Overview

| Folder/File | Description |
|-------------|-------------|
| `tests/` | Predefined tests executed through CI/CD pipelines |
| `features/` | Gherkin feature files and step definitions |
| `.github/workflows/` | GitHub Actions configuration for CI |
| `.tekton/` | Tekton tasks for continuous delivery |
| `service/` | Core application logic (routes, models, configs) |
| `static/` | UI assets (CSS, JS, HTML) |
| `Dockerfile`, `Makefile` | Automation for build and container run |
| `.flaskenv`, `Procfile` | App configuration and startup setup |

---

## Template & Credits

This project is based on the [TDD/BDD Final Project Template](https://github.com/VitaliiaPalchei/xgcyk-tdd-bdd-final-project-template) originally created by [John Rofrano](https://github.com/jrofrano) at IBM.  
Licensed under the Apache License 2.0.

---

## Maintained by

**Vitaliia Palchei** – QA Engineer with experience in functional testing, accessibility, API validation, and CI/CD automation.  
[LinkedIn](https://linkedin.com/in/vitaliia-palchei) | [GitHub](https://github.com/VitaliiaPalchei)

---

## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

John Rofrano, Senior Technical Staff Member, DevOps Champion, @ IBM Research

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>
