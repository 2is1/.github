# Contributing to 2is1

Welcome to the **2is1** organization! 🚀 

We are a development organization focused on building diverse and innovative applications. Currently, our portfolio includes:
*   **Options Categorizer**
*   **Offside**

Whether you are fixing a bug, adding a new feature, or improving documentation, we highly value your contributions. This document outlines the guidelines and workflows for contributing to our projects.

---

## 🔒 1. Access and Confidentiality

Because our repositories are **private**, our contribution workflow differs slightly from open-source projects.

*   **Getting Access:** You must be invited to the `2is1` GitHub organization or granted explicit read/write access to a specific repository. If you need access, please contact the organization: team@tier-list.click
*   **Confidentiality:** All code, discussions, issues, and documentation within this organization are strictly confidential. Do not share code snippets, architecture details, or project roadmaps outside of the organization without explicit permission.
*   **No Public Forks:** Please do not fork private repositories into public personal accounts. All branching and pull requests must remain within the private organization ecosystem.
*   **Never push directly to `master` or `dev` branches.** All changes must go through a Pull Request.

---

## 🛠 2. Development Workflow

We follow a standard feature-branch workflow to keep our `main` branches stable.

### Step-by-Step Guide:
1.  **Sync your local repo:** Always ensure your local `dev` branch is up to date.
    ```bash
    git switch dev
    git pull
    ```
2.  **Create a branch:** Create a new branch for your work. Use a meaningful naming convention:
    *   `task-related-name`
    ```bash
    git switch -c task-related-name
    ```
3.  **Make your changes:** Write clean, documented, and tested code.
4.  **Commit your changes:** Write clear and concise commit messages.
    ```bash
    git commit -m "add categorization filter for options"
    ```
5.  **Push to GitHub:**
    ```bash
    git push origin task-related-name
    ```
6.  **Create the Pull Request to dev branch on GitHub.**

---

## 📦 3. Project-Specific Guidelines

Since we develop different kinds of apps, please refer to the specific setup instructions in the `README.md` of the project you are working on.

### Options Categorizer
*   **Focus:** This app allows you to create, sort, and search different categories, as well as import and export them.
*   **Tech Stack:** React, Node.js, Typescript, PostgreSQL, Capacitor
*   **Local Setup:** Refer to the `Options Categorizer` README for environment variable requirements and installation steps.

### Offside
*   **Focus:** Offside is a football prediction platform.
*   **Tech Stack:** React, Node.js, Typescript, React-Native, PostgreSQL
*   **Local Setup:** Refer to the `Offside` README for environment variable requirements and installation steps.

---

## 📥 4. Pull Request Process

When you are ready to merge your changes, open a Pull Request (PR) against the `dev` branch.

*   **Title:** Use a clear title (e.g., `Fix: Resolve crash on login screen`).
*   **Description:** Fill out the PR template. Explain *what* you changed and *why*.
*   **Link Issues:** If your PR resolves an existing issue, link it using keywords (e.g., `Resolved #42`).
*   **Self-Review:** Review your own code diff before requesting a review from others.
*   **Testing:** Ensure all existing BDD tests pass and add new BDD tests for new features.

---

## 🐛 5. Reporting Bugs and Requesting Features

*   **Bug Reports:** Open an issue in the respective repository. Include:
    *   A clear, descriptive title.
    *   Steps to reproduce the behavior.
    *   Expected vs. actual behavior.
    *   Screenshots or error logs (ensure no sensitive data/keys are included).
*   **Feature Requests:** Open an issue labeled `High`. Describe the use case and how it adds value to the application.

---

## 💻 6. Coding Standards

While specific linting rules may vary between **Options Categorizer** and **Offside**, all contributors should adhere to the following principles:

*   **Readability:** Write code that is easy for others to understand. Use meaningful variable and function names.
*   **Comments:** Comment complex logic, but avoid stating the obvious. Let the code speak for itself where possible.
*   **Security:** Never commit secrets, API keys, or passwords. Use `.env` files and ensure they are in the `.gitignore`.
*   **DRY (Don't Repeat Yourself):** Abstract reusable logic into shared functions or components.

---

## 💬 7. Communication

If you are stuck, have a question, or want to discuss an architectural decision:
*   Comment on the relevant GitHub Issue.
*   Reach out via our communication email: team@tier-list.click

---

Thank you for helping us build great software at **2is1**!