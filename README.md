# 🚀 Git Branching & Workflow Practical Demo

This repository showcases a hands-on demonstration of essential Git operations, specifically focusing on **branching**, **switching**, **creating new branches**, **staging**, **committing**, **pushing changes**, **pulling updates**, **merging branches**, and **resolving merge conflicts**.

---

## 📁 Project Structure

The project contains a sample directory with files used to demonstrate Git operations.

![Directory View](directory.png)

---

## 🌿 Creating and Switching Branches

Two branches were created and used in this demonstration:
- `update-navigation`
- `add-contact-info`

To create and switch to a new branch named `update-navigation`:

```bash
git branch update-navigation
git switch update-navigation
```

Alternatively, use:
```bash
git checkout -b update-navigation
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
git commit -m "Updated index and added Jerry's work"
```

![Index File Change](index-file.png)

![Jerry's Work File](jerry's-work.png)

---

## 📤 Pushing to GitHub

After committing locally, the changes were pushed to GitHub:

```bash
git push origin update-navigation
```

Repeat the same steps for the `add-contact-info` branch:

```bash
git checkout -b add-contact-info
git add .
git commit -m "Added contact information"
git push origin add-contact-info
```

![GitHub Repository](repository.png)

---

## ⬇️ Pulling Updates from GitHub

To ensure the local branch is up to date, pull updates from GitHub:

```bash
git pull origin main
```

![Pull Request](pull-request.png)

---

## 🔀 Merging Branches

To merge changes from branches into the `main` branch:

```bash
git checkout main
git merge update-navigation
git merge add-contact-info
```

![Merge Branches](merge-branches.png)

---

## ⚠️ Resolving Merge Conflicts

If merge conflicts occur, manually resolve conflicts within affected files, then stage and commit the resolution:

```bash
# resolve conflicts manually
git add .
git commit -m "Resolved merge conflicts"
```

![Resolving Conflicts](resolving-conflicts.png)

---

## 🔗 Summary

This practical session covered:

- ✅ Creating and switching branches (`update-navigation`, `add-contact-info`)  
- ✅ Making and tracking file changes  
- ✅ Staging and committing changes  
- ✅ Pushing to a remote GitHub repository  
- ✅ Pulling updates from a remote repository
- ✅ Merging branches
- ✅ Resolving merge conflicts

These are essential skills for managing code in collaborative environments and maintaining clean, organized version histories.

---

## 🛠️ Technologies Used

- Git (CLI)
- GitHub
- VS Code

---

## 📎 GitHub Repository

> [https://github.com/Salsdev/ai-startup-website](https://github.com/Salsdev/ai-startup-website)

---

Feel free to explore the repository and follow along with the screenshots and commit history for deeper understanding.