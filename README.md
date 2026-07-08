<div align="center">

# ♟️ AUPP Chess Club Election Management System

### A lightweight, serverless election platform built for the American University of Phnom Penh Chess Club.

Designed to provide a secure, transparent, and organized voting experience for club elections while remaining simple to maintain for future student committees.

---

![HTML5](https://img.shields.io/badge/Frontend-HTML5-orange?logo=html5)
![CSS3](https://img.shields.io/badge/Style-CSS3-blue?logo=css3)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow?logo=javascript)
![Google Apps Script](https://img.shields.io/badge/Backend-Google%20Apps%20Script-green?logo=google)
![Google Sheets](https://img.shields.io/badge/Database-Google%20Sheets-success?logo=googlesheets)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

</div>

---

# 📖 Overview

The **AUPP Chess Club Election Management System** is a web-based election platform created to replace generic online voting methods with a dedicated solution designed specifically for the American University of Phnom Penh (AUPP) Chess Club.

The platform allows club members to participate in organized elections while enabling club officers to efficiently manage candidates, voting records, and election results.

Rather than relying on third-party forms, the system was developed to provide a more structured, transparent, and sustainable election process for future generations of the club.

---

# 🎯 Why I Built This

While serving as a **Chess Club Officer**, I noticed that our club relied on general-purpose online forms to conduct elections.

I wanted to build something that belonged to the club.

Instead of using Google Forms every semester, I designed a dedicated election platform that could continue serving future committees long after I graduate.

The goal was simple:

- Create a better voting experience
- Improve election transparency
- Reduce administrative work
- Build something future students could continue using

---

# ✨ Features

## 👤 Member Features

- Secure voting portal
- Position-based voting
- One submission per voter
- Clean and intuitive interface
- Organized election workflow

---

## 🛠 Administrator Features

- Candidate management
- Election management
- Participation tracking
- Election result generation
- Voter record management

---

# 🏗 System Architecture

```
Club Member
      │
      ▼
HTML / CSS / JavaScript
      │
      ▼
Google Apps Script
      │
      ▼
Google Sheets
```

Google Apps Script acts as the backend service that processes requests from the website and stores election data securely inside Google Sheets.

---

# 🛠 Technology Stack

| Category | Technology |
|----------|------------|
| Frontend | HTML5 |
| Styling | CSS3 |
| Programming | JavaScript |
| Backend | Google Apps Script |
| Data Storage | Google Sheets |
| Version Control | Git & GitHub |

---

# 💡 Design Decisions

Instead of using a traditional SQL database, this project intentionally uses **Google Sheets** as its data store.

This decision was made because:

- Future club officers may not have database experience.
- Google Sheets is easy to understand and maintain.
- No server-side database needs to be managed.
- Deployment costs remain minimal.
- Election records can be reviewed quickly when needed.

For a student organization, maintainability was prioritized over unnecessary complexity.

---

# 🚀 Challenges

The most challenging part of development was designing the election logic.

The system needed to:

- Separate elections by position.
- Prevent overlapping votes.
- Store voting records correctly.
- Generate election results.
- Display voter participation accurately.

Building this workflow required multiple rounds of testing and refinement.

---

# 🌍 Project Impact

Unlike many academic projects, this system was built to solve a real organizational problem.

It provides the AUPP Chess Club with a dedicated election platform that future committees can continue using instead of relying on generic online voting tools.

The project reflects my interest in building software that delivers practical value beyond the classroom.

---

# 📚 What I Learned

This project strengthened my understanding of:

- Frontend web development
- JavaScript programming
- Google Apps Script
- Google Sheets integration
- Event-driven programming
- User interface design
- Problem solving
- Software architecture
- Building software for real users

More importantly, it taught me that successful software engineering is about creating systems that people can easily understand, use, and maintain.

---

# 📸 Screenshots

> Screenshots will be added soon.

Suggested images:

- Login Page
- Voting Page
- Candidate Selection
- Election Results
- Administrator Dashboard

---

# 🔮 Future Improvements

Planned enhancements include:

- Mobile responsive design
- QR Code login
- Email notifications
- Election scheduling
- Multi-language support
- Audit logs
- Enhanced administrator dashboard
- Improved reporting and analytics

---

# 📌 Project Status

🟢 **Active**

The project is currently maintained by the original developer.

The long-term goal is to transfer administrative ownership to future AUPP Chess Club officers to ensure continuity.

---

# 👨‍💻 Developer

## Lishang Keav

Former AUPP Chess Club Officer  
**January 2026 – May 2026**

Bachelor of Computer Science  
**Fort Hays State University**

Bachelor of Information Technology Management  
**American University of Phnom Penh**

GitHub

https://github.com/Lishang-Keav

---

# 🤝 Acknowledgements

Special thanks to:

- American University of Phnom Penh
- AUPP Chess Club
- Faculty Advisors
- Club Committee Members
- Everyone who tested and provided feedback

---

# 📄 License

This project was developed for educational and organizational purposes.

Future AUPP Chess Club committees are encouraged to continue maintaining and improving this platform while preserving attribution to the original developer.

---

<div align="center">

*"Building software that serves people—not just assignments."*

</div>
