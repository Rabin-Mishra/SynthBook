**Here is the complete, ready-to-copy `CONTRIBUTING.md` file** for your SynthBook project:

```markdown:disable-run
## Contributing Guidelines

You are **Awesome!** Thank you for your interest in contributing to **SynthBook** 🤗

We follow the [GitHub Flow](https://guides.github.com/introduction/flow/) for contributions.

## Contents
- [Setting Up the Project](#setting-up-the-project)
- [Contributing](#contributing)

### Setting Up the Project

1. The project works best with **Python 3.8+**.
2. (Optional) [Fork](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) the repository.
3. Clone the repository:
   ```bash
   git clone https://github.com/Rabin-Mishra/SynthBook.git
   ```
4. Navigate to the project directory:
   ```bash
   cd SynthBook
   ```
5. (Optional) Create a new feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
6. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
7. Apply database migrations:
   ```bash
   python manage.py migrate
   ```
8. Run the development server:
   ```bash
   python manage.py runserver
   ```
   You're good to go! 🎉

📝 If you face any difficulties while setting up the project, please [raise an issue](https://github.com/Rabin-Mishra/SynthBook/issues).

#### Optional Setup
- [Setting up Google Authentication](https://django-allauth.readthedocs.io/en/latest/installation.html)
- [Setting up SMTP for Emails](https://youtu.be/-tyBEsHSv7w)
- [Creating Superuser](https://www.geeksforgeeks.org/how-to-create-superuser-in-django/)

---

### Contributing

- Please go through [GitHub Flow](https://guides.github.com/introduction/flow/) if you're new to open source contributions.
- Look for an existing [Issue](https://github.com/Rabin-Mishra/SynthBook/issues) or [create a new one](https://github.com/Rabin-Mishra/SynthBook/issues/new).
- Discuss your proposed changes and get assigned.
- Work on your branch (`feature/your-feature-name`).
- After making changes:
  - Run tests and linting:
    ```bash
    flake8
    python manage.py test
    ```
  - Stage and commit only the relevant files.
  - Push your changes:
    ```bash
    git push origin feature/your-feature-name
    ```
- Go to the repository and create a **Pull Request** with a clear and detailed description.
- Once reviewed and approved, your PR will be merged.

**Thank you for contributing to SynthBook!** ❤️

---


```
