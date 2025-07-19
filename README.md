# 🚀 Git Branching & Workflow Practical Demo

This repository showcases a hands-on demonstration of basic Git operations, specifically focusing on **branching**, **switching**, **creating new branches**, **staging**, **committing**, and **pushing changes** to a remote repository.

---

## 📁 Project Structure

The project contains a sample directory with files used to demonstrate Git operations.

![Directory View](directory.png)

---

## 🌿 Creating and Switching Branches

To create and switch to a new branch named `feature-branch`:

```bash
git branch feature-branch
git switch feature-branch
```

Alternatively, use:
```bash
git checkout -b feature-branch
```

![Creating Branch](creating-branch.png)

You can view available branches using:

```bash
git branch
```

![Branches List](branches.png)

---

## 📝 Making Changes and Tracking Status

Changes were made to files in the repository (e.g., `index.html`, `jerry-work.txt`), and Git was used to track these updates.

```bash
git status
```

This shows modified, new, and untracked files:

![Git Status](git-status.png)

---

## 🗃️ Staging and Committing Changes

To stage and commit the changes:

```bash
git add .
git commit -m "Updated index and added jerry's work"
```

![Index File Change](index-file.png)

![Jerry's Work File](jerry's-work.png)

---

## 📤 Pushing to GitHub

After committing locally, the changes were pushed to GitHub:

```bash
git push origin feature-branch
```

![GitHub Repository](repository.png)

---

## 🔗 Summary

This practical session covered:

- ✅ Creating and switching branches  
- ✅ Making and tracking file changes  
- ✅ Staging and committing changes  
- ✅ Pushing to a remote GitHub repository  

These are essential skills for managing code in collaborative environments and maintaining clean, organized version histories.

---

## 🛠️ Technologies Used

- Git (CLI)
- GitHub
- VS Code

---

## 📎 GitHub Repository

> [(https://github.com/Salsdev/ai-startup-website)]

---

Feel free to explore the repository and follow along with the screenshots and commit history for deeper understanding.
