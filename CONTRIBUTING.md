# Contributing to Chatroom Web Page

This repository enforces **hyper-strict contribution guidelines**. Every contributor must read and follow these rules. Contributions that do not comply will be rejected without exception.  

By participating, you agree to adhere to all rules outlined below. Maintainers reserve the right to **modify, update, or delete this CONTRIBUTING.md file or any guidelines at any time**, without prior notice.

---

## 1. General Contribution Principles

1. **Relevance**: Only submit contributions that directly improve, fix, or enhance this project. Off-topic or experimental submissions are not allowed.  
2. **Completeness**: All contributions must be fully functional and complete. Partial, broken, or placeholder code is strictly forbidden.  
3. **Professionalism**: Contributors must maintain respectful, professional communication at all times. Harassment, offensive language, or inappropriate content is strictly prohibited.  
4. **Legal Compliance**: Submissions must not contain malware, pirated content, copyrighted material without permission, or illegal content. Violations will result in immediate rejection and reporting.  
5. **Ownership and Rights**: By contributing, you agree that your work can be used, modified, and redistributed under the same open-source license as this repository.  

---

## 2. Workflow Rules

- **Fork the repository** before making any changes.  
- **Branching is mandatory**:  
```bash
git checkout -b feature/your-feature-name
```
- **Direct commits to `main` are prohibited.**  
- **Pull requests must target `main` only** and include a clear, descriptive title.  
- **One logical change per pull request**. Combining multiple unrelated features is not allowed.  
- Maintainers may **close or reject PRs that do not follow this workflow**.  

---

## 3. Code Standards

### HTML
- Semantic and valid HTML only.  
- Properly close all tags and maintain correct nesting.  
- Indentation must be consistent.  
- Avoid inline styles unless explicitly approved.  
- Remove placeholders and commented-out code.  

### CSS
- Use clear, descriptive class and ID names.  
- Keep styles modular and organized.  
- Avoid redundancy and unused rules.  
- Follow the project’s existing styling conventions.  

### JavaScript
- Use descriptive variable and function names.  
- Avoid global variables unless necessary.  
- All scripts must be tested and run error-free.  
- Remove console logs and debug code before submission.

### General
- Consistent indentation, spacing, and formatting across all files.  
- Comment code **only when necessary**; redundant comments are not allowed.  
- All files must use UTF-8 encoding.  
- Follow existing folder and file structure strictly.  

---

## 4. Testing Requirements

- Test all changes in **at least two modern desktop browsers** (Chrome, Firefox, Edge, Safari).  
- Ensure all functional features (chat iframe, TOS popup, footer links) continue working.  
- Visual inspection is mandatory: layout, alignment, and styling must be intact.  
- Regression testing is required to confirm no existing functionality is broken.  
- JavaScript must execute without errors or warnings in the console.  

---

## 5. Documentation Rules

- Every new feature or change must be reflected in `README.md` or appropriate project documentation.  
- Update task lists if functionality changes.  
- Contributions that modify functionality without updating documentation will be **rejected automatically**.  

---

## 6. Pull Request Guidelines

- Titles must clearly indicate the purpose of the PR.  
- Descriptions must explain what was changed and why.  
- Reference related issues where applicable.  
- Only one logical change per PR; multiple unrelated changes will be rejected.  
- All PRs are subject to code review; maintainers may request changes before merging.  

---

## 7. Examples of Contributions That Will Be Rejected

- Submissions containing syntax errors or untested code.  
- Pull requests that break existing features.  
- Irrelevant or off-topic contributions.  
- Offensive, inappropriate, or illegal content.  
- Bypassing code review or ignoring feedback from maintainers.  
- Submissions lacking documentation for functional changes.  
- Pull requests containing commented-out code or console/debug logs.  
- Contributions that do not follow the repository workflow or branching rules.  

---

## 8. Suggested Contributions

- Test the site on multiple browsers.  
- Make footer links open in a modal.  
- Customize chat iframe appearance.  
- Add a welcome message or greeting when the chat loads.  
- Improve overall styling while maintaining the theme.  

---

## 9. Pull Request Checklist

Before submitting a pull request, ensure:

- [ ] Code is complete and fully functional.  
- [ ] Changes are relevant and improve the project.  
- [ ] Code is clean, readable, and follows all standards.  
- [ ] All testing requirements are met.  
- [ ] Documentation is updated if functionality changed.  
- [ ] Pull request contains a clear, descriptive explanation.  
- [ ] No commented-out code, debug statements, or placeholders remain.  

---

## 10. Maintainers’ Authority

- Maintainers reserve the right to **reject, modify, or delete any contributions** (including pull requests, branches, or forks) at any time, for any reason.  
- Contributors **cannot dispute or override** these actions.  
- Any non-compliant or low-quality submissions may result in immediate deletion of your fork, branch, or related PR.  
- Maintainers may **modify, update, or remove this CONTRIBUTING.md file** at any time without notice.  
- By contributing, you acknowledge and accept that all submissions are subject to maintainers’ discretion and may be removed or altered at any time.  

---

## 11. License

By contributing, you agree that your contributions will be licensed under the same **open-source license** as this repository.  

---

**Strict adherence to all rules is mandatory. Any contribution failing to comply will be rejected without exception. Maintainers’ decisions are final.**
