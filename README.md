# TinySchoolHub 🏫

Welcome to **TinySchoolHub**, a modern, lightweight school communication platform designed for teachers and parents.

## 🎯 About the Project

TinySchoolHub aims to simplify school management and communication through a secure, Kubernetes-native platform. Key features include:

- 📋 **Class Management**: Organize students and rosters.
- 📸 **Photo Sharing**: Share school moments securely with parents.
- 🕒 **Absence Tracking**: Simple workflow for tracking student attendance.
- 💬 **Messaging**: Secure communication channel between educators and families.

## 🏗️ Project Structure

The project is split into several repositories:

- [tiny-school-hub-api-backend](../tiny-school-hub-api-backend): Go-based backend API.
- [tiny-school-hub-frontend](../tiny-school-hub-frontend): React-based frontend application.
- [tiny-school-hub-tooling](../tiny-school-hub-tooling): **Centralized orchestration** and development stack (Makefile, Docker Compose).
- [tiny-school-hub-wiki](../tiny-school-hub-wiki): Additional documentation and guides.

## 🚀 Getting Started

To set up the full development environment, please head over to the **[tiny-school-hub-tooling](../tiny-school-hub-tooling)** repository. It provides the necessary tools to run the entire backend and frontend stack with a single command.

## 🛠️ Development & Committing

Currently, the project is in its initial development phase. 

- **Commit Strategy**: We are currently committing **directly to the `main` branch**. 
- **Collaboration**: As a solo project for now, this approach allows for rapid iteration.

> [!NOTE]
> High-level architecture and cross-repo orchestration are managed in the `tiny-school-hub-tooling` repository.
