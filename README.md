# [cite_start]Assignment Summary: Continuous Integration and GitHub Actions [cite: 1]

[cite_start]This guide summarizes all the steps, source code files, and workflow configurations required to complete the home assignment for CI and GitHub Actions[cite: 1, 3].

---

## [cite_start]Part 1: Continuous Integration with GitHub Actions [cite: 5]

### [cite_start]Task 1: Repository Setup & Basic Workflow [cite: 9]
[cite_start]**Objective:** Create a new GitHub repository, initialize it with a `README.md` file, and set up a basic workflow that triggers on every push to the `main` branch to print a verification message in the logs[cite: 7, 8, 10, 15].

#### 1. Required Project Structure:
```text
ci-github-actions-demo/
├── .github/
│   └── workflows/
│       └── basic.yml
└── README.md
