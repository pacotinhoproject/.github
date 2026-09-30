<div align="center">

<img src="https://github.com/pacotinhoproject/.github/blob/main/profile/assets/pacotinho_asking.png?raw=true" alt="Pacotinho Project" width="250">

# Contributing to Pacotinho Project

</div>

Pacotinho Project is an open-source organization focused on **networking, cybersecurity, and software development**.

Contributions can be code, documentation, ideas, bug reports, or improvements.

---

## Before you start

Before making a change:

1. Check existing **Issues** and **Discussions**.
2. For larger changes, open an Issue or Discussion first.
3. Keep changes focused on one purpose.
4. Do not modify unrelated files.

Small fixes and documentation changes can usually go directly into a Pull Request.

---

## How to contribute

### 1. Fork the repository

Create your own fork of the repository you want to contribute to.

### 2. Clone your fork

```bash
git clone https://github.com/YOUR-USERNAME/REPOSITORY.git
cd REPOSITORY
```

### 3. Create a branch

Do not work directly on `main`.

Use a descriptive branch name:

```text
feature/add-project-section
fix/mobile-menu
docs/update-readme
refactor/project-card
test/add-login-tests
```

Recommended format:

```text
type/short-description
```

### 4. Make your changes

Follow the existing structure, style, and conventions of the repository.

### 5. Test your changes

Before opening a Pull Request:

* Make sure the project still works.
* Run the available tests.
* Check for errors.
* Check the changes on mobile when relevant.
* Make sure you did not modify unrelated files.

### 6. Commit your changes

Follow the [Commit Convention](#commit-convention).

### 7. Push your branch

```bash
git push origin your-branch-name
```

### 8. Open a Pull Request

Explain:

* What changed.
* Why it was changed.
* How it was tested.
* Related Issue, if applicable.

---

## Commit Convention

Pacotinho Project follows a simple **Conventional Commits** style.

Format:

```text
type: short description
```

Example:

```text
feat: add project section
fix: resolve mobile menu issue
docs: update README
style: improve project cards
refactor: simplify project loader
test: add UserService tests
```

### Commit types

| Type       | Description                                                             | Example                             |
| ---------- | ----------------------------------------------------------------------- | ----------------------------------- |
| `feat`     | Adds a new feature.                                                     | `feat: add project section`         |
| `fix`      | Fixes a bug or problem.                                                 | `fix: resolve mobile menu issue`    |
| `docs`     | Changes documentation.                                                  | `docs: update README`               |
| `style`    | Changes formatting or visual appearance without changing functionality. | `style: improve project cards`      |
| `refactor` | Changes code structure without changing behavior.                       | `refactor: simplify project loader` |
| `test`     | Adds or modifies tests.                                                 | `test: add UserService tests`       |
| `chore`    | Maintenance changes that do not affect the application.                 | `chore: update dependencies`        |
| `build`    | Changes related to the build system or dependencies.                    | `build: update build configuration` |
| `ci`       | Changes to CI/CD configuration.                                         | `ci: add GitHub Actions workflow`   |

### Commit rules

* Use English.
* Start with a type.
* Use the imperative form.
* Keep the description short.
* Do not end the subject with a period.
* Keep one logical change per commit.

Good:

```text
feat: add project card
fix: resolve navbar overflow
docs: add contribution guide
```

Avoid:

```text
updated stuff
fixes
changes
final version
update
asdf
```

---

## Pull Requests

Keep Pull Requests focused whenever possible.

A Pull Request should:

* Have a clear title.
* Explain what changed.
* Explain why the change was made.
* Include tests or verification when applicable.
* Reference an Issue when applicable.

### Pull Request title

Use the same commit convention:

```text
feat: add project section
fix: resolve mobile layout
docs: update contributing guide
```

Avoid combining unrelated changes into one Pull Request.

---

## Issues

Use Issues for:

* Bug reports.
* Feature requests.
* Improvements.
* Tasks.
* Technical problems.

Before opening an Issue, search existing Issues to avoid duplicates.

When reporting a bug, include:

* What happened.
* What you expected.
* Steps to reproduce.
* Relevant environment information.
* Screenshots or logs when useful.

---

## Discussions

Use Discussions when an issue does not require a code change yet.

### Ideas

Use **Ideas** for:

* New projects.
* New features.
* Tools.
* Experiments.
* Improvements.

### Questions

Use **Questions** for:

* Questions about projects.
* Questions about contributing.
* Technical questions.

### General

Use **General** for other discussions related to Pacotinho Project.

---

## Code and Project Guidelines

* Follow the existing structure of the repository.
* Follow existing formatting and naming conventions.
* Prefer simple solutions.
* Avoid unnecessary dependencies.
* Do not commit passwords, API keys, tokens, or other secrets.
* Do not commit generated files unless the project requires them.
* Keep changes related to the purpose of the Pull Request.
* Update documentation when your change affects how something works.

---

## Questions

If you are unsure about something, open a Discussion before making a large change.

For security vulnerabilities, follow the instructions in [`SECURITY.md`](https://github.com/pacotinhoproject/.github/blob/main/SECURITY.md).

For community behavior, see [`CODE_OF_CONDUCT.md`](https://github.com/pacotinhoproject/.github/blob/main/CODE_OF_CONDUCT.md).

---

## License

Each repository may have its own license.

Check the repository's `LICENSE` file before using or redistributing its code.
