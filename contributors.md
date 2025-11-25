# Driver Buddy – Team Report

**Members:** Mairesse, Aasmi, Aavash, Madiha  
**Date:** 2025-11-25  

## 1. Release Process

Our team followed a professional release process using Git Flow and semantic versioning to ensure a structured and reliable delivery:

### Feature Development

All development was done in feature branches off `develop`. Features included:

- Student Carpool Matching (route-based matching and optional extra rider notifications)  
- Verified Student Profiles (university email verification, driver background checks)  
- Smart Scheduling (automatic ride suggestions, class schedule integration, notifications)  
- In-App Chat & Rating System (coordinate pickups, rate drivers/riders, report issues)  
- Eco-Friendly Incentives (Green Points, CO₂ tracking, campus rewards)  
- Subscription & Freemium Model (affordable plans with unlimited rides and premium features)
 

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

| Team Member | Role | Contribution |
|------------|------|-------------|
| **Madiha** | Problem Analysis | Explained main transportation challenges: high costs, limited options, wasted car capacity, lack of networking opportunities |
| **Mairesse** | Development | Designed and partially implemented Student Carpool Matching and Affordable Subscription System; GPS-based route matching, timing coordination, environmental benefits; planned class schedule integration |
| **Aasmi** | Development | Implemented Smart Scheduling, designed in-app Chat & Rating system, and Eco-Friendly Incentives; encouraged sustainable commuting |
| **Aavash** | Monetization | Implemented Subscription Plans and Freemium Model; outlined potential University Partnerships and financial benefits |


## 3. Lessons Learned

- **Professional Git Practices:** Branching, release branches, tagging, and semantic versioning ensure structured development.  
- **Code Quality & Hooks:** Husky pre-commit hooks, lint-staged, and commitlint maintain consistent code style and commit messages.  
- **Documentation:** Clear README and CHANGELOG improve usability and maintainability.  
- **Collaboration:** Even with a small team, structured use of issues and project boards facilitated task tracking.  
- **Recovery Awareness:** Practiced Git reflog, bisect, and cherry-pick to safely recover from mistakes.


## 4. Future Improvements

- **Automated CI/CD:** Run automated tests, generate coverage reports, and build releases automatically.  
- **Mobile App Deployment:** Publish Driver Buddy to iOS/Android app stores for real user testing.  
- **Expanded Features:** Multi-campus route optimization, in-app payments, and enhanced notifications/reminders.  
- **Security & Compliance:** Implement privacy and safety checks, integrate two-factor authentication for drivers.  


