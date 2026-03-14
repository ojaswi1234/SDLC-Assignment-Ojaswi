# SDLC-Assignment-Ojaswi

## Project Overview
The "Smart-Attend" mobile app is a student attendance tracker designed for a university startup. Initially, the project was scoped to mark attendance automatically using Geo-fencing when a student enters a classroom. Midway through development, a new requirement was introduced: integrating Biometric (Face ID) verification to prevent proxy attendance. This repository outlines the shift from a Waterfall methodology to an Agile (Scrum) framework to successfully accommodate this late-stage requirement.

## Repository Contents
* `DevOps Assignment 1 (Analysis).pdf`: A detailed analysis explaining why the Waterfall model would fail for this project and why an Agile approach (Scrum) is the optimal solution.
* `backlog.csv`: The Sprint Backlog containing prioritized user stories and estimated hours for the team.

## CI/CD Pipeline Justification
To effectively deliver the Sprint 2 (Biometric Update) to students automatically, a CI/CD (Continuous Integration / Continuous Deployment) pipeline is essential. 

### Continuous Integration (CI)
When the development team writes the new code for Face ID integration, they will commit it to the shared repository. The CI pipeline will automatically trigger a build process and run automated regression tests. This ensures that the new camera and biometric logic does not conflict with or break the existing background Geo-fencing logic developed in Sprint 1. If any tests fail, the team is notified immediately, preventing buggy code from merging into the main branch.

### Continuous Deployment (CD)
Once the CI pipeline confirms the new code is stable and passes all tests, the CD pipeline takes over. It automatically compiles the final application package (APK for Android or IPA for iOS) and pushes the update directly to the respective App Stores or internal test devices. This eliminates the need for manual, error-prone release processes, ensuring that students and teachers receive the critical Biometric security update quickly and seamlessly.