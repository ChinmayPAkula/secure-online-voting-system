# Secure Online Voting Platform

A full-stack web application designed to simulate a secure online voting system.
This project focuses on core software engineering concepts such as authentication,
authorization, backend–frontend interaction, database design, and security-aware
problem solving using Python and Flask.

The goal of this project is to build a realistic system that demonstrates how
secure voting workflows can be designed and enforced in a web application.

---

## Core Features

### Authentication
- User signup and login system
- Secure password hashing (passwords are never stored in plain text)
- Session-based authentication

### Ballot Management
- Authenticated users can create voting ballots
- Each ballot is assigned a unique identifier (UID)
- Ballots contain a configurable list of candidates

### Voting System
- Users can vote only after logging in
- Voting is performed using a ballot UID or direct ballot link
- One-user-one-vote enforcement per ballot
- Vote confirmation after successful submission

### Results
- Ballot creators can view voting results
- Results are computed dynamically from stored votes

---

## Security Concepts Implemented

- **Password Hashing:** Secure storage of user credentials using cryptographic hashing
- **Authentication vs Authorization:** Clear separation between identity verification
  and permission enforcement
- **Session Management:** Secure handling of logged-in user state
- **Vote Integrity:** Prevention of duplicate voting using backend validation
- **Input Validation:** Defensive checks against invalid or malicious inputs

---

## Tech Stack

### Backend
- Python
- Flask
- SQLite

### Frontend
- HTML
- CSS
- Minimal JavaScript (optional, for progressive enhancement)

---

## Project Structure

<pre>
secure-online-voting-system/
│
├── backend/
│   ├── app.py        # Flask application entry point
│   ├── auth.py       # Authentication logic (login/signup)
│   ├── voting.py    # Ballot creation and voting logic
│   └── database.py  # Database connection and queries
│
├── frontend/
│   ├── index.html   # Landing / results page
│   ├── login.html   # Login and signup page
│   ├── vote.html    # Voting interface
│   └── style.css    # Basic styling
│
├── requirements.txt
└── README.md
</pre>

---

## Project Status

🚧 **In Progress**

This project is actively being developed to strengthen backend development skills,
understand full-stack system design, and practice security-conscious programming.
---
