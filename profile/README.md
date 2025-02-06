# Empleo Digno

## Overview

Empleo Digno is an AI-driven HR pipeline designed with a conversational approach to streamline job recruitment and application processes. The project consists of three main repositories that work together to create a seamless experience for both job seekers and employers.

## Repositories

### 1. **Apply**

- **Purpose**: Designed for individuals seeking job opportunities.
- **Features**:
  - User registration and profile management.
  - Job application tracking.
  - AI-powered job recommendations.
  - Application status updates.

### 2. **Recruit**

- **Purpose**: Built for businesses looking to publish job listings and manage applicants.
- **Features**:
  - Job posting and management.
  - Candidate tracking and application review.
  - AI-assisted candidate recommendations.
  - Interview scheduling and applicant status updates.

### 3. **Middleware**

- **Purpose**: Serves as the hub connecting **Apply** and **Recruit**, handling external API integrations and data synchronization.
- **Features**:
  - Centralized authentication and authorization.
  - API communication between Apply and Recruit.
  - Logging and analytics handling.

## Technology Stack

- **Frontend**: Next.js, Tailwind CSS
- **Backend**: FastAPI, Python
- **Database**: MongoDB
- **Infrastructure**: AWS, Docker, GitHub Actions for CI/CD
- **Authentication**: JWT

## Contribution Guidelines

1. Clone the relevant repository.
2. Follow the setup instructions in the respective `README.md`.
3. Ensure all commits follow the **conventional commit** format (**fix**, **feat**, **refactor**, etc.).
4. **Pull requests (PRs) are mandatory for all changes**—no direct commits to protected branches.
5. Each PR must be reviewed and approved before merging.

## Security & Compliance

- The repositories **Apply** and **Recruit** enforce **branch protection rules**, requiring pull requests to be reviewed before merging.
