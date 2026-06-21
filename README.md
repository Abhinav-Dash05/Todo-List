# 🔐 Secure To-Do List

⚠️ **Disclaimer:** This project was developed for educational purposes to explore secure software development, authentication systems, encryption techniques, and cybersecurity concepts in Python. It is not intended for production use without additional security review, testing, and hardening.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Security](https://img.shields.io/badge/Security-Focused-green)
![Encryption](https://img.shields.io/badge/Fernet-Encrypted-success)
![Authentication](https://img.shields.io/badge/Argon2-Protected-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

A security-focused command-line task management application built in Python. Over six iterations, the project evolved from a basic to-do list into a secure multi-user application featuring authentication, encrypted storage, password hashing, activity logging, and task organization tools.

---

# 🎯 Project Goals

This project was built to gain practical experience with:

- Secure authentication systems
- Password hashing
- Data encryption
- Secure file storage
- User account management
- Defensive programming
- Python application development
- Software security practices

Rather than focusing only on functionality, the project explores how cybersecurity concepts can be integrated into everyday software.

---

# ✨ Features

## 👤 Account Management

- User registration
- User login
- Multiple account support
- Persistent account storage
- Username hashing using SHA-256
- User-specific task storage

## 🔒 Security Features

- Argon2 password hashing
- Fernet encrypted task storage
- SHA-256 username hashing
- Login attempt limiting
- Automatic password rehashing when required
- Activity logging system
- Secure credential handling
- Separation of user data and task storage

## ✅ Task Management

- Add tasks
- View tasks
- Delete tasks
- Clear task lists
- Mark tasks as completed
- Persistent task storage across sessions

## 📋 Organization Features

- High-priority tasks
- Low-priority tasks
- Due dates
- Due times
- Status tracking
- Pending task reminders
- Task filtering and display formatting

## 💾 Data Persistence

- Encrypted task storage
- Automatic save/load functionality
- Separate task files per user
- Persistent credential storage
- Activity logging

---

# 🛡 Security Implementation

## Password Protection

Passwords are secured using Argon2, a modern password hashing algorithm designed to resist brute-force and hardware-accelerated attacks.

Passwords are never stored in plaintext.

## Data Encryption

Task data is encrypted using Fernet before being written to disk.

This helps protect stored task information from casual inspection.

## Username Protection

Usernames are stored using SHA-256 hashes rather than plaintext identifiers.

## Login Protection

The application limits failed login attempts and introduces delays to reduce the effectiveness of simple brute-force attacks.

## File Management

The application stores credentials, encryption keys, logs, and task data in dedicated application directories to improve organization and separation of sensitive information.

---

# 🏗 Project Evolution

This repository contains multiple versions documenting the development process.

| Version | Main Focus |
|----------|------------|
| To-Do List 1.0 | Basic task management |
| To-Do List 2.0 | Improved functionality |
| To-Do List 3.0 | Better task organization |
| To-Do List 4.0 | Expanded account features |
| To-Do List 5.0 | Security improvements |
| To-Do List 6.0 | Authentication, encryption, logging, and secure storage |

Each version represents a step toward improved functionality, maintainability, and security.

---

# ⚙ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Core application |
| Argon2 | Password hashing |
| Cryptography (Fernet) | Data encryption |
| SHA-256 | Username hashing |
| File Handling | Persistent storage |
| GitHub CodeQL | Static analysis |
| GitHub Actions | Workflow automation |
| Dependabot | Dependency monitoring |

---

# 📁 Repository Structure

```text
Todo-List/
│
├── PROJECT 1 (TO-DO LIST)
├── PROJECT 2 (TO-DO LIST 2.0)
├── PROJECT 3 (TODO LIST 3.0)
├── PROJECT 4 (TODO LIST 4.0)
├── PROJECT 5 (TO-DO LIST 5.0)
├── PROJECT 6 (TO-DO LIST 6.0)
│
├── .github/
│   ├── workflows/
│   └── dependabot.yml
│
├── SECURITY.md
├── LICENSE
└── README.md
```

---

# 🚀 Running the Project

## Clone the Repository

```bash
git clone https://github.com/Abhinav-Dash05/Todo-List.git
```

## Navigate to the Project

```bash
cd Todo-List
```

## Install Dependencies

```bash
pip install argon2-cffi cryptography
```

## Run Version 6

```bash
python "PROJECT 6 (TO-DO LIST 6.0)/TO-DO.py"
```

---

# 📚 Learning Outcomes

Through this project I gained practical experience with:

- Password hashing and verification
- Encryption and secure storage
- Authentication system design
- Secure file handling
- Activity logging
- Multi-user application design
- GitHub security tooling
- Software maintenance and versioning

---

# 🔮 Future Improvements

- Per-user encryption keys
- Database backend
- Graphical User Interface (GUI)
- Two-factor authentication (2FA)
- Secure password recovery
- Audit log enhancements
- Automated security testing

---

# 🌐 Cybersecurity Relevance

This project demonstrates the practical implementation of foundational cybersecurity concepts, including:

- Authentication
- Password security
- Encryption
- Secure storage
- Access control
- Security-focused software development

While fundamentally a task management application, it was developed as a platform for learning and applying security principles in real software systems.

---

# 👨‍💻 Author

**Abhinav Dash**

Student Developer • Python Programmer • Cybersecurity Enthusiast

---

## License

Copyright © 2025 Abhinav Dash

Licensed under the Apache License, Version 2.0.

See the LICENSE file for details.
