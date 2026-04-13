# Submission Requirement and Task Allocation

## 📌 Submission Requirement

This is a **pair (two-person) activity**. Both members are expected to work collaboratively to complete the lab.

- You must create **one shared GitHub repository** for the project.
- Both members must actively contribute to the repository.
- Contributions should be visible through:
  - commits
  - file changes
  - updates or feature additions
- The repository must contain all required files organised in a folder named:

```text
312Lab3
```

### ✅ Important

- **Only ONE member will submit** the final GitHub repository link via Moodle.
- However, the repository must clearly reflect contributions from **BOTH members**.
- Both names must be included in:
  - the homepage (`index.html`), or
  - `README.md`
- The final repository submitted must be:
  - complete
  - accessible
  - working properly

---

## 👥 Task Allocation (Guide Only)

The task division below is provided as a **guide only**.

> You are free to divide the work differently based on your own agreement as a pair.  
> If you have already decided among yourselves who will do which part, that is fine.  
> However, the **GitHub repository must clearly reflect contributions from both members**.

### 🔹 Member 1 – Structure and Core Setup (Suggested)

Member 1 may focus on the main website structure and the initial setup of the project.

Suggested tasks:
- create `index.html` (Home page)
- create `about.html` (About Us page)
- set up the Bootstrap starter template
- create the navigation bar used across all pages
- implement the jumbotron or hero section on the homepage
- use the Bootstrap grid system to organise content
- create the external CSS file
- apply Bootstrap spacing classes for margins and padding
- add images and apply the `img-fluid` class
- include jQuery `document.ready()` in assigned pages

### 🔹 Member 2 – Content and Enhancements (Suggested)

Member 2 may focus on the content, design improvements, and additional requirements.

Suggested tasks:
- create `innovations.html`
- add content on future technologies and innovations
- apply Bootstrap text utility classes for styling text
- extend the CSS styling for consistency and design improvement
- include jQuery `document.ready()` in assigned pages
- research other Bootstrap classes not covered in class
- document the Bootstrap findings in `README.md` or in an appropriate section of the project
- test the website on mobile, tablet, and desktop viewports

---

## 🤝 Shared Responsibilities

Both members are expected to:

- discuss and agree on how the work will be divided
- review each other's work
- ensure that all marking criteria are covered
- maintain a consistent design across all pages
- test the final website together
- ensure both names are included in the project
- ensure the GitHub repository clearly shows input from both members

---

## 🗂 Suggested Project Structure

Your repository may be organised like this:

```text
312Lab3/
├── index.html
├── innovations.html
├── about.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   └── ...
└── README.md
```

---

## 🔧 GitHub Workflow (Step-by-Step for Beginners)

The steps below are provided to help students who are new to GitHub and Git.

---

## 1. Create the Repository (Member 1 Only)

One group member should create the repository first.

Steps:
1. Log in to GitHub
2. Click **New repository**
3. Enter the repository name:

```text
312Lab3
```

4. Choose whether the repository will be **Public** or **Private**
5. Click **Create repository**

---

## 2. Add the Second Member as a Collaborator

After the repository is created:

1. Open the repository on GitHub
2. Go to **Settings**
3. Click **Collaborators**
4. Add your partner using their GitHub username
5. Your partner must accept the invitation before contributing

---

## 3. Clone the Repository to Your Computer

Both members should clone the shared repository to their own computers.

```bash
git clone https://github.com/your-username/312Lab3.git
cd 312Lab3
```

This downloads the shared project folder to your computer.

---

## 4. Check the Current Branch

You can check which branch you are currently on by using:

```bash
git branch
```

The active branch will usually show as `main`.

---

## 5. Always Pull the Latest Changes First

Before starting new work, always download the latest version of the repository.

```bash
git pull origin main
```

This helps prevent conflicts and ensures you are working on the most recent version.

---

## 6. Create Your Own Working Branch

Each student should work on their own branch instead of directly editing the `main` branch.

Example:

```bash
git checkout -b feature-homepage
```

or

```bash
git checkout -b feature-innovations
```

### What this means
- `git checkout -b` creates a new branch
- it also switches you into that branch immediately

---

## 7. Confirm You Are on the Correct Branch

Use:

```bash
git branch
```

The branch with `*` next to it is the one you are currently using.

---

## 8. Make Your Changes

Now create or edit your files as needed.

Examples:
- add HTML content
- update CSS styling
- add images
- edit JavaScript or jQuery

---

## 9. Check What Has Changed

Before committing, you can see the files you changed by running:

```bash
git status
```

This shows:
- modified files
- new files
- files ready to be committed

---

## 10. Add Files to the Staging Area

To prepare your changes for commit, use:

```bash
git add .
```

### What this means
- `git add .` adds all changed files in the current folder

If you want to add only one file, you can use:

```bash
git add index.html
```

---

## 11. Commit Your Work

After adding your files, save a snapshot of your work with a commit message.

```bash
git commit -m "Added homepage structure and navbar"
```

### Important
Your commit message should clearly explain what you changed.

Good examples:
- `git commit -m "Created about page"`
- `git commit -m "Added Bootstrap grid layout"`
- `git commit -m "Updated CSS styling"`
- `git commit -m "Added innovations page content"`

---

## 12. Push Your Branch to GitHub

Upload your branch and commits to GitHub using:

```bash
git push origin feature-homepage
```

Replace `feature-homepage` with the name of your own branch.

---

## 13. Create a Pull Request on GitHub

After pushing your branch:

1. Open the repository on GitHub
2. GitHub may show a button saying **Compare & pull request**
3. Click it
4. Review your changes
5. Submit the pull request

A pull request is used to request that your branch changes be merged into the `main` branch.

---

## 14. Merge the Pull Request

After reviewing the work:

1. Click **Merge pull request**
2. Confirm the merge

This combines the branch work into the `main` branch.

---

## 15. Update Your Local Main Branch After Merge

After work has been merged, update your local `main` branch.

```bash
git checkout main
git pull origin main
```

This ensures your computer has the latest merged version.

---

## 16. Repeat the Process

For every new task:
1. pull the latest changes
2. create a branch
3. make changes
4. add files
5. commit
6. push
7. create pull request
8. merge
9. pull latest changes again

---

## ✅ Simple Daily Workflow Summary

Use this as your regular workflow:

```bash
git pull origin main
git checkout -b feature-branch
git add .
git commit -m "your message"
git push origin feature-branch
```

After merge:

```bash
git checkout main
git pull origin main
```

---

## 📘 Example Branch Names

Students can use simple branch names like:

- `feature-homepage`
- `feature-about-page`
- `feature-innovations-page`
- `feature-css-update`
- `feature-jquery`
- `feature-responsive-fix`

---

## 📘 Example Commit Messages

Students should use simple and clear commit messages such as:

- `Added homepage layout`
- `Created about page`
- `Added innovations content`
- `Updated navbar`
- `Improved CSS styling`
- `Added responsive images`
- `Included jQuery document ready`
- `Fixed spacing issue on mobile`

---

## ⚠ Important Rules for Pair Work

- Always pull before starting work
- Do not work directly on `main` unless necessary
- Work on your own branch
- Commit regularly
- Use meaningful commit messages
- Do not overwrite your partner's work
- Communicate with your partner before editing the same file at the same time
- Make sure both members contribute to the repository

---

## 🧠 If There Is a Conflict

Sometimes Git may show a conflict if both students edit the same part of the same file.

If this happens:
1. do not panic
2. talk to your partner
3. open the file and review the conflicting sections
4. keep the correct content
5. save the file
6. add, commit, and push again



## 🚀 Final Checklist Before Submission

Before submitting, make sure that:

- [ ] all 3 pages are completed (`index.html`, `innovations.html`, `about.html`)
- [ ] Bootstrap components are correctly used
- [ ] external CSS is applied
- [ ] jQuery is included
- [ ] images are responsive using `img-fluid`
- [ ] margins and padding are properly applied
- [ ] additional Bootstrap class research is included
- [ ] the website works on mobile, tablet, and desktop
- [ ] both names are included in the project
- [ ] GitHub shows contributions from both members
- [ ] the repository link works
- [ ] the final version is complete and working

---

## 📎 Final Submission

- Submit **ONLY ONE GitHub repository link** via Moodle.
- Only one member is required to submit.
- However, the submission represents the work of **both members**.
- Make sure the repository is complete, accessible, and clearly shows contributions from both students.
