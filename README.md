<div align="center">

# ♟️ AUPP Chess Club Election Management System

*A lightweight, serverless election platform built for the American University of Phnom Penh (AUPP) Chess Club.*

![HTML5](https://img.shields.io/badge/Frontend-HTML5-orange?logo=html5)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow?logo=javascript)
![Google Apps Script](https://img.shields.io/badge/Backend-Google%20Apps%20Script-green?logo=google)
![Google Sheets](https://img.shields.io/badge/Data-Google%20Sheets-success?logo=googlesheets)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

</div>

---

# 📖 Overview

The **AUPP Chess Club Election Management System** is a web-based voting platform developed for the American University of Phnom Penh (AUPP) Chess Club.

The project was created to replace generic online voting forms with a dedicated election platform designed specifically for student club elections.

Instead of relying on third-party survey tools, this system provides a simple and organized workflow that allows eligible Chess Club members to submit their votes while making election management easier for club officers.

---

# Why This Project Was Built

While serving as an AUPP Chess Club Officer (January 2026 – May 2026), I worked closely with the Vice President to help organize club operations.

One recurring challenge was managing officer nominations and elections. Existing tools such as Google Forms could collect responses, but they were not designed for the club's election workflow or long-term use.

I proposed developing a dedicated election platform that would:

- Organize candidate nominations
- Conduct officer elections in one place
- Record voting information in an organized manner
- Generate election results more efficiently
- Provide a reusable system for future Chess Club committees

The goal was not to build a complex system, but to create a practical solution for a real organizational need within the club.

---

# ✨ Features

## Member Features

- Simple voting interface
- Name verification
- Student ID verification
- AUPP email verification
- Position-based voting
- Easy-to-use design

---

## Election Management

- Candidate management
- Organized election workflow
- Vote recording
- Participation tracking
- Election result generation

---

# 🗳 Voting Workflow

The election process follows a simple workflow:

1. Member enters:
   - Full Name
   - Student ID
   - AUPP Email Address

2. Member selects candidates for the available positions.

3. Vote is submitted.

4. Google Apps Script processes the request.

5. Election records are stored in Google Sheets.

6. Results can be viewed after the election.

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

Google Apps Script acts as the server-side component by receiving requests from the website and storing election data in Google Sheets.

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

This project intentionally uses **Google Apps Script** and **Google Sheets** instead of a traditional backend server and SQL database.

For a student organization, this approach offers several advantages:

- No dedicated server required
- Easy deployment
- Low maintenance
- Easy access for future committee members
- Google Sheets provides a familiar interface for reviewing election data

The focus was to create a practical solution that balances simplicity, reliability, and maintainability.

---

# 🚀 Challenges

One of the biggest challenges during development was designing the voting workflow.

The system needed to:

- Separate election positions correctly
- Record votes accurately
- Store election records
- Display election results
- Track voting participation

Testing and refining these processes helped ensure the system worked reliably during elections.

---

# 🌍 Project Impact

Unlike many classroom projects, this system was developed to solve a real need within a student organization.

The platform provides the AUPP Chess Club with a dedicated election system that can continue serving future club committees instead of relying on generic online forms.

The goal was to create software that delivers practical value beyond the classroom.

---

# 📚 What I Learned

Developing this project strengthened my understanding of:

- Frontend web development
- JavaScript
- Google Apps Script
- Google Sheets integration
- User interface design
- Workflow design
- Problem solving
- Building software for real users

This project also taught me that software engineering is not only about writing code, but about designing systems that people can easily use and maintain.

---

## Demonstration

The platform is used during official AUPP Chess Club elections.

Because the most recent election cycle has concluded, screenshots of the live voting process are not currently included. Documentation and demonstration materials will be updated during future election periods.
---

# 🔮 Future Improvements

Potential future enhancements include:

- Mobile responsive design
- QR Code access
- Email notifications
- Better administrator dashboard
- Election analytics
- Audit logging
- Multi-language support

---

# 📌 Project Status

🟢 Active

The project is intended to support future AUPP Chess Club elections.

Administrative ownership is planned to be transferred to future Chess Club officers when appropriate.

---

# 👨‍💻 About the Developer

**Lishang Keav**

Former AUPP Chess Club Officer  
**January 2026 – May 2026**

Bachelor of Computer Science  
Fort Hays State University (FHSU)

Bachelor of Information Technology Management  
American University of Phnom Penh (AUPP)

GitHub:

https://github.com/Lishang-Keav

---

# 🤝 Acknowledgements

Special thanks to:

- American University of Phnom Penh
- AUPP Chess Club
- Faculty Advisors
- Club Committee Members
- Everyone who participated in testing and feedback

---

# 📄 License

This project was developed for educational and organizational purposes.

Future AUPP Chess Club committees are welcome to continue maintaining and improving this platform while preserving attribution to the original developer.

---

<div align="center">

### "Building software that solves real problems for real people."

</div>
