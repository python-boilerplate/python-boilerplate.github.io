# Contributing Guide

Welcome!
Thank you for your interest in improving **python-boilerplate/uv-template**. This project is my personal template, and **only bug fixes are accepted**.

---

## 🐞 Reporting a Bug

Before submitting a bug report:

- **Check** that the issue hasn’t already been reported in the [Issues](https://github.com/python-boilerplate/uv-template/issues) section.

When reporting a bug, please include:

- **Steps to reproduce** the bug
- **Expected** vs **actual** behavior
- Any **logs, error traces, or screenshots** (if applicable)
- Details about your **Python version**, **OS**, and any relevant environment info

> Clear, detailed bug reports or feature descriptions help address problems faster.

---

## 🔄 How to Contribute (Pull Request)

1. **Fork** this repository to your own GitHub account.
2. **Create a branch** for your fix.  
   _Branch naming suggestion:_ `fix/short-bug-description`
3. **Apply your changes** on that branch (**_if it's a bug_**).
4. **Test your code**:
    - Run the test suite:  
      ```bash
      make test
      ```
    - Run the linter:  
      ```bash
      make lint && make format
      ```
5. **Describe your PR** clearly and informatively.
6. **Open a Pull Request** from your branch to this repository.

---

## ✅ Code Requirements

!!! success "!"

    - **Follow the existing code style.**
    - **Make sure all tests pass** (`pytest`) (if needed).
    - **Lint and Format your code** with `ruff` before submitting (if needed).
    - **Do not** add new features or change existing functionality without agreement.

---

## ❓ Questions

!!! question "!"

    If you have questions about contributing,  
    please [open an issue](https://github.com/python-boilerplate/uv-template/issues/new) or comment on an existing one.

---

Thank you for helping make this template better!