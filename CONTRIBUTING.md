# Contributing

Thank you for your interest in contributing to **AWS Infrastructure Dashboard**.

We welcome bug reports, feature suggestions, documentation improvements, and pull requests that help improve the platform.

---

## Reporting Issues

Before opening a new issue, please:

- Search existing issues to avoid duplicates.
- Provide a clear description of the problem.
- Include steps to reproduce the issue.
- Specify your environment (Python version, operating system, AWS service, etc.).
- Attach logs or screenshots when applicable.

---

## Development Workflow

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature/my-feature
```

3. Install project dependencies.

```bash
pip install -r requirements.txt
```

4. Make your changes.

5. Verify everything works correctly before submitting.

6. Commit using descriptive commit messages.

```bash
git commit -m "Add CloudWatch widget improvements"
```

7. Push your branch.

```bash
git push origin feature/my-feature
```

8. Open a Pull Request.

---

# Coding Standards

Please keep contributions:

- Clean and readable
- Well documented
- Backward compatible whenever possible
- Consistent with the existing project structure

---

# Testing

Run the unit tests before submitting a Pull Request.

```bash
coverage run -m unittest discover
coverage report
coverage erase
```

---

# Security

If you discover a potential security vulnerability, please do **not** create a public issue.

Instead, contact the project maintainer privately with:

- vulnerability description
- affected component
- reproduction steps
- possible mitigation

---

# Feature Requests

Suggestions are always welcome.

Good feature requests include:

- Business use case
- Expected behavior
- Possible implementation
- Benefits for users

---

# Project Roadmap

Community contributions are especially welcome in areas such as:

- Additional AWS service support
- Infrastructure visualization
- Dashboard templates
- Performance improvements
- CLI enhancements
- Documentation
- Testing

---

# License

By contributing to this repository, you agree that your contributions will be licensed under the project's MIT License.
