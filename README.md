````markdown
# 💻 Open Source Contribution Practice Repo

Welcome to the Open Source Contribution Practice Repository!  
This repo is designed to help beginners learn how to use Git, GitHub, and VS Code to contribute to open source projects.

---

## 🌱 Objective

Learn to:
- Fork and clone a GitHub repository
- Work with Git branches
- Commit changes from VS Code
- Open a pull request (PR)
- Follow open-source contribution etiquette

---

## 🚀 How to Contribute

Follow these steps to make your first contribution:

### ✅ 1. Fork the Repository

- Click the **Fork** button (top right) to create your own copy of this repo.

### ✅ 2. Clone Your Fork

```bash
git clone https://github.com/<your-username>/open-source-practice.git
cd open-source-practice
code .
````

### ✅ 3. Create a New Branch

```bash
git checkout -b feature/your-name
```

Example:

```bash
git checkout -b feature/jane-doe
```

### ✅ 4. Add Your Name to CONTRIBUTORS.md

Open `CONTRIBUTORS.md` and add your name in the following format:

```markdown
- Jane Doe – [janedoe](https://github.com/janedoe)
```

### ✅ 5. Stage, Commit, and Push

```bash
git add CONTRIBUTORS.md
git commit -m "Add: Jane Doe to contributors list"
git push origin feature/your-name
```

### ✅ 6. Create a Pull Request (PR)

* Go to your forked repo on GitHub
* Click **Compare & pull request**
* Add a message and click **Create pull request**

Once your PR is reviewed, it will be merged into the main repo 🎉

---

## 📂 Project Structure

```plaintext
open-source-practice/
├── CONTRIBUTORS.md       # You will add your name here
├── README.md             # This file
└── .github/
    └── ISSUE_TEMPLATE/
        └── add-name.yml  # Good First Issue template (optional)
```

---

## 🛠 Useful Git Commands

```bash
# Clone your fork
git clone <fork-url>

# Check current branch
git branch

# Create and switch to new branch
git checkout -b feature/your-name

# Stage changes
git add <file>

# Commit changes
git commit -m "Your message"

# Push to your branch
git push origin feature/your-branch
```

---

## 🙋 Need Help?

* Ask questions in the Issues section
* Use the `good first issue` label to find beginner-friendly tasks
* Follow [GitHub Docs](https://docs.github.com/en/get-started/quickstart) for more guidance

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

Happy contributing! 💙
Maintainer – [Bhavana Jami](https://github.com/iambluewonk)

```

---

Let me know if you'd like me to also generate this as a GitHub repository template for you to push directly.
```
