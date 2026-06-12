# DevOps Project 12: CI/CD Pipeline for Node.js Web Application

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Runtime](https://img.shields.io/badge/node-%3E%3D14.0.0-blue)
![Tools](https://img.shields.io/badge/tools-Docker%20%7C%20Jenkins%20%7C%20GitHub-orange)

This repository contains a lightweight, production-ready Node.js web application integrated with a complete CI/CD automation pipeline. The project demonstrates containerization practices using Docker and automated build/deployment stages using Jenkins.

## 🚀 Application & Pipeline Overview

* **Application:** A fast and responsive REST API / Web Server built with **Node.js** and Express (`server.js`).
* **Containerization:** Packaged cleanly using a optimized **Dockerfile** for seamless deployment across environments.
* **Automation:** Automated workflow handled via a programmatic `Jenkinsfile` (Pipeline-as-Code) to manage testing, security checks, building, and deployment stages.

---

## 🛠️ Tech Stack & Tools

* **Backend Runtime:** Node.js
* **Dependency Management:** npm (`package.json`)
* **Containerization:** Docker
* **CI/CD Automation:** Jenkins (Declarative Pipeline)
* **Source Control:** GitHub

---

## 📂 Project Structure

```text
├── .gitignore          # Rules for ignoring build and node_modules files in Git
├── Dockerfile          # Step-by-step instructions to containerize the Node.js app
├── Jenkinsfile         # DevOps pipeline script for automated builds & testing
├── package.json        # Project metadata, scripts, and npm dependencies
└── server.js           # Core application server logic and API endpoints
