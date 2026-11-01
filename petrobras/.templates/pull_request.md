# 🚀 Pull Request Template
<!-- Thank you for contributing! Please fill in the sections below clearly to help reviewers understand your changes. -->
## 📝 General Description
<!-- Provide an objective summary of the purpose of this PR. What does it solve? What is the impact? -->
## 🎯 Type of Change
<!-- Mark with an 'X' the applicable option -->
- [ ] ✨ Feat: New feature/functionality (Non-breaking change).
- [ ] 🐛 Fix: Bug fix (Non-breaking change).
- [ ] ♻️ Refactor: Change that neither fixes a bug nor adds a feature (Code improvement/cleanup).
- [ ] ⚡ Perf: Code change focused purely on performance.
- [ ] 🎨 Style: Change in formatting, spacing, variable names (No change to logic).
- [ ] 🧪 Test: Addition, fix, or update of unit/integration tests.
- [ ] 📝 Docs: Changes exclusively in documentation (README, API docs, etc.).
- [ ] 🚀 Chore/Infra: Changes to configuration files, CI/CD, dependencies, or build tools.
- [ ] 💥 Breaking Change: Modification that breaks compatibility with previous versions.
## 🔗 Context & Links
<!-- Indicate related issues, cards (Jira, Trello), or discussions -->
- Fixes/Closes / Related to: #
## 🛠️ Technical Details & Architecture (Optional)
<!-- Describe relevant architecture decisions, new dependencies added, or approaches adopted. -->
- 
## 🧪 Testing Plan & Evidence
<!-- Explain in detail how reviewers can validate this PR and attach proof. -->
### How to test manually:
1. Switch to the PR branch: git checkout <branch-name>
2. Make sure to update the environment: git pull origin <base-branch> (and update dependencies if necessary)
3. Run the command: ...
4. Scenario to validate: 
### Evidence (Images, GIFs, or Console Logs):
<details>
<summary>📸 Click here to expand and view</summary>
Insert logs, command outputs, or paste images/GIFs here
</details>
---
## ✅ Developer Checklist
<!-- Please validate all points below before requesting review. -->
- [ ] Synchronization: My branch is up to date with the target branch (dev, main, etc.).
- [ ] Code Standard: The code follows the style guidelines, linters, and conventions established in the project.
- [ ] Self-review: I reviewed my own changes line by line before opening the PR (avoiding unnecessary commits or temporary comments).
- [ ] Impact: I assessed the impact of these changes on other parts of the system and on database (if applicable).
- [ ] Documentation: I updated the documentation and comments in complex code snippets, if necessary.
- [ ] Tests: I wrote new tests or made sure existing tests cover the changes.
- [ ] Success: All local tests and automated validations passed without errors or warnings.
