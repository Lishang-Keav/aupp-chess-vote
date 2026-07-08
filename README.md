# ♟️ AUPP Chess Club Election Management System

A lightweight, serverless web application developed for the **American University of Phnom Penh (AUPP) Chess Club** to conduct secure, transparent, and organized club elections.

---

## 📖 Overview

The AUPP Chess Club Election Management System was created to replace generic online forms with a dedicated election platform tailored specifically for the Chess Club.

The system allows eligible members to vote for:

- President
- Vice President
- Club Officers

using a structured voting workflow while keeping election records organized in Google Sheets.

Unlike traditional web applications, this project uses **Google Apps Script** and **Google Sheets** instead of a dedicated backend server or SQL database, making it simple to maintain for future club committees.

---

# 🎯 Objectives

This project was designed to:

- Replace generic online voting forms.
- Provide a dedicated election system.
- Improve election transparency.
- Organize candidate management.
- Record election participation.
- Preserve election records.
- Create a long-term solution for future Chess Club committees.

---

# ✨ Features

## Member

- Secure voting interface
- Position-based voting
- One submission per member
- Simple and intuitive interface

## Administration

- Candidate management
- Election management
- Vote tracking
- Participation records
- Election result generation

---

# 🛠 Technology Stack

## Frontend

- HTML5
- CSS3
- Vanilla JavaScript

## Backend

- Google Apps Script

## Data Storage

- Google Sheets

## Version Control

- Git
- GitHub

---

# 🏗 System Architecture

```
Member
    │
    ▼
HTML Website
    │
    ▼
Google Apps Script
    │
    ▼
Google Sheets
```

Google Apps Script acts as the backend service by receiving requests from the website, processing election data, and storing records inside Google Sheets.

---

# 💡 Why Google Apps Script?

This project intentionally uses Google Apps Script rather than a traditional backend because it offers several advantages for a student organization.

- No server maintenance
- No SQL database required
- Easy deployment
- Easy maintenance
- Low operating cost
- Future committee members can manage election data using Google Sheets without requiring database knowledge

The goal was to build a solution that balances simplicity, reliability, and maintainability.

---

# 🚀 Challenges

The most challenging aspect of this project was designing the election logic.

The system needed to correctly:

- separate election positions
- record votes
- prevent duplicate submissions
- calculate results
- display participation records
- maintain election integrity

Developing this workflow required careful planning and testing.

---

# 🌍 Project Impact

Unlike many academic projects, this system was built to solve a real organizational problem.

It provides the AUPP Chess Club with a dedicated election platform that future club committees can continue using instead of relying on general-purpose online forms.

---

# 📚 Lessons Learned

This project strengthened my understanding of:

- Frontend web development
- JavaScript
- Google Apps Script
- Google Sheets integration
- API communication
- Event-driven programming
- Software architecture
- Real-world software development
- Building software for actual users

---

# 👨‍💻 Developer

**Lishang Keav**

Former AUPP Chess Club Officer  
**January 2026 – May 2026**

Bachelor of Computer Science  
Fort Hays State University

Bachelor of Information Technology Management  
American University of Phnom Penh

---

# 📌 Project Status

Active

This project is intended to serve future generations of the AUPP Chess Club.

Administrative ownership will be transferred to future Chess Club officers when appropriate.

---

# 📄 License

Educational and organizational use only.

Future Chess Club committees are welcome to maintain and improve this project while preserving attribution to the original developer.

---

> *Designed to support fair, transparent, and efficient elections for the AUPP Chess Club—today and for future generations.*
