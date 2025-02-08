# Contributing to Ilhampay

Thank you for considering contributing to **Ilhampay**! 🚀 Your contributions are greatly appreciated and will help build a robust and secure payment gateway.

## 📌 Table of Contents

- [How to Contribute](#how-to-contribute)
- [Project Structure](#project-structure)
- [Branching & Git Workflow](#branching--git-workflow)
- [Code Guidelines](#code-guidelines)
- [Setting Up Your Development Environment](#setting-up-your-development-environment)
- [Submitting a Pull Request (PR)](#submitting-a-pull-request-pr)
- [Issue Reporting](#issue-reporting)

---

## 🚀 How to Contribute

1. **Fork the repository** and clone it to your local machine.
2. **Create a new branch** for your feature or bug fix.
3. **Write clean, well-documented code**.
4. **Test your changes** before submitting.
5. **Submit a Pull Request (PR)** following the guidelines below.

---

## 📂 Project Structure

```
/ilhampay
│── mobile-app/          # Flutter app source code
│── web-dashboard/       # React.js admin panel
│── backend/             # FastAPI/Node.js backend
│── database/            # PostgreSQL & Firestore schema
│── .github/workflows/   # GitHub Actions for CI/CD
│── README.md            # Project documentation
│── CONTRIBUTING.md      # Contribution guidelines
│── LICENSE              # License details
```

---

## 🔀 Branching & Git Workflow

- ``** branch**: Production-ready code only.
- ``** branch**: Active development.
- **Feature branches**: Create a new branch for each feature/fix.

**Branch Naming Conventions:**

```
feature/payment-integration
bugfix/qr-code-error
hotfix/api-security-patch
```

### **Commit Message Guidelines**

Format: `type(scope): description`

```
feat(payments): Added DuitNow QR code scanner
fix(auth): Fixed Firebase authentication issue
chore(docs): Updated README with setup instructions
```

---

## 🔧 Code Guidelines

- Follow **Flutter best practices** for UI development.
- Use **Prettier & ESLint** for clean JavaScript/TypeScript code.
- Follow **REST API principles** for backend development.
- Write **unit tests** before submitting a PR.

---

## 🛠️ Setting Up Your Development Environment

### 🔹 Prerequisites

- **Flutter SDK** → [Install Guide](https://flutter.dev/docs/get-started/install)
- **Node.js & npm** → [Download Here](https://nodejs.org/)
- **Python 3 & FastAPI** → `pip install fastapi`
- **Firebase CLI** → `npm install -g firebase-tools`
- **Docker (Optional for Backend)** → [Install Here](https://www.docker.com/)

### 🔹 Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/drksrv/ilhampay.git
cd ilhampay
```

2. **Set up Flutter dependencies**

```bash
flutter pub get
```

3. **Run the mobile app**

```bash
flutter run
```

4. **Set up backend (FastAPI/Node.js)**

```bash
cd backend
pip install -r requirements.txt   # If using FastAPI
npm install                       # If using Node.js
npm start                          # Start the backend server
```

---

## 🔄 Submitting a Pull Request (PR)

1. **Ensure your code is tested and documented**.
2. **Push your changes to your branch**:

```bash
git add .
git commit -m "feat(payment): Added Stripe integration"
git push origin feature/payment-integration
```

3. **Create a Pull Request (PR) on GitHub**.
4. **Wait for review and address feedback**.

---

## 🐞 Issue Reporting

If you encounter a bug or have a feature request, **create an issue**:

- **Describe the problem clearly**.
- **Provide steps to reproduce (if applicable)**.
- **Attach logs/screenshots** (if needed).

---

## ✅ Next Steps

- Follow **GitHub Discussions** for project updates.
- Join our **Slack/Discord community** *(coming soon!)*.
- Thank you for contributing to Ilhampay! 🚀

