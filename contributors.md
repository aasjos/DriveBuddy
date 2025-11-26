# Driver Buddy – Team Report

**Members:** Mairesse, Aasmi, Aavash, Madiha  
**Date:** 2025-11-25  

## 1. Release Process  

Our team followed a structured **Git Flow workflow**, semantic versioning, protected branches, and PR reviews to deliver a production ready release.


### Feature Development

All development was done in feature branches off `develop`. Features included:

- Student Carpool Matching (route-based matching and optional extra rider notifications)  
- Verified Student Profiles (university email verification, driver background checks)  
- Smart Scheduling (automatic ride suggestions, class schedule integration, notifications)  
- In-App Chat & Rating System (coordinate pickups, rate drivers/riders, report issues)  
- Eco-Friendly Incentives (Green Points, CO₂ tracking, campus rewards)  
 

### Versioning

Semantic versioning (MAJOR.MINOR.PATCH) was applied:  

- `v0.1.0`: First working prototype  
- `v0.2.0`: Core features added  
- `v1.0.0`: Complete release  

### Release Preparation

- Created a release branch `release/v1.0.0` from `develop`.  
- Updated `package.json` version and `CHANGELOG.md`.  
- Only critical bug fixes applied during release preparation.  
- Merged release branch into `main` and tagged `v1.0.0`.  

### Submission

- Created a submission tag: `assignment3-final`.  
- Verified that all tags and releases appear correctly on GitHub.  
- Live demo link: [https://demo-link.com](https://demo-link.com)  

---

## 2. Team Contributions  

| Team Member | Role | Contribution Summary |
|------------|------|---------------------|
| **Madiha** | Problem Analysis | Identified key transportation issues and user pain-points (cost, availability, car capacity, and networking gaps). Authored problem and motivation sections. |
| **Mairesse** | Development | Implemented major parts of **Student Carpool Matching**, **Driver Verification**, and **Subscription Model**. Contributed heavily to HTML/JS integration and repository structure. |
| **Aasmi** | Development | Implemented core logic for **Smart Scheduling**, designed **In-App Chat & Rating System**, and built **Eco-Friendly Incentives** framework. Led Git Flow setup, branch protection, release management, PR reviews, and contribution tracking. |
| **Aavash** | Monetization | Designed Subscription Tiers and Freemium model, proposed University partnerships and financial benefits strategy. |


## 3. Lessons Learned  

- **Git Workflow Mastery:**  
  Learned how feature branches, release branches, PR reviews, and protected branches enhance stability and collaboration.

- **Release Management:**  
  Practiced semantic versioning, tagging, changelog maintenance, and structured release delivery.

- **Documentation & Collaboration:**  
  Creating clear README, CHANGELOG, and contributors documentation improved team alignment.

- **Error Recovery:**  
  Used Git reflog, bisect, and cherry-pick to diagnose and recover from mistakes.

- **Agile Collaboration:**  
  Using Issues + Project Board streamlined task assignment, progress tracking, and coordinated development.


## 4. Future Improvements

- **Automated CI/CD:** Run automated tests, generate coverage reports, and build releases automatically.  
- **Mobile App Deployment:** Publish Driver Buddy to iOS/Android app stores for real user testing.  
- **Expanded Features:** Multi-campus route optimization, in-app payments, and enhanced notifications/reminders.  
- **Security & Compliance:** Implement privacy and safety checks, integrate two-factor authentication for drivers.  




