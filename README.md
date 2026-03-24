# 🚀 Commit Automation Setup (Git Hooks, Linting & Versioning)

This project demonstrates how to improve code quality and automate development workflows using Git hooks, linting tools, and versioning.

---

## 📌 Features

* ✅ Enforces standard commit messages
* ✅ Automatically checks and fixes code before commit
* ✅ Formats code consistently
* ✅ Runs checks only on changed files
* ✅ Generates version updates and changelog

---

## 🧰 Tech Stack

* **Husky** → Git Hooks
* **Commitlint** → Commit message validation
* **ESLint** → Code quality checking
* **Prettier** → Code formatting
* **lint-staged** → Runs tasks on staged files
* **standard-version** → Versioning & changelog

---

## ⚙️ Project Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/SyedRoshannn/commit-demo.git
cd commit-demo
```

---

### 2️⃣ Install dependencies

```bash
npm install
```

---

### 3️⃣ Initialize Husky

```bash
npm run prepare
```

---

## 🧪 Usage

### ✔ Commit changes

```bash
git add .
git commit -m "feat: add new feature"
```

👉 Automatically:

* Runs ESLint
* Formats code using Prettier
* Validates commit message

---

### ✔ Run versioning

```bash
npm run release
```

👉 Automatically:

* Updates version
* Generates `CHANGELOG.md`
* Creates Git tag

---

## 📁 Project Structure

```
commit-demo/
│
├── .husky/                # Git hooks
├── commitlint.config.js   # Commit message rules
├── eslint.config.mjs      # ESLint configuration
├── .prettierrc            # Prettier configuration
├── .prettierignore        # Ignore formatting
├── CHANGELOG.md           # Auto-generated changelog
├── package.json           # Scripts & dependencies
└── test.js                # Sample file
```

---

## 📊 Example Commit Format

```bash
feat: add login feature
fix: resolve API issue
docs: update README
```

❌ Invalid:

```bash
updated code
```

---

## 📈 Versioning Example

| Version | Description     |
| ------- | --------------- |
| 1.0.0   | Initial setup   |
| 1.1.0   | Feature updates |
| 1.1.1   | Bug fixes       |

---

## 🎯 Benefits

* Improves code quality
* Ensures consistency
* Saves developer time
* Makes collaboration easier
* Automates release process

---

## 🙌 Author

**Syed Roshan**
GitHub: https://github.com/SyedRoshannn

---

## ⭐ Conclusion

This project provides a complete automated workflow for modern development using Git hooks, linting, formatting, and version control best practices.

It ensures that every commit is clean, structured, and production-ready.
