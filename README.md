# CSP451 CheckPoint 1

## Description

This project is a small static website created for CSP451 CheckPoint 1. It demonstrates the basics of Git, GitHub, version control, and a feature-branch workflow. The project uses HTML, CSS, and JavaScript, and it is managed with Git using Conventional Commit messages.

The purpose of this repository is to show how a local project can be initialized with Git, committed in stages, pushed to GitHub, documented with Markdown, and updated through a pull request workflow.

## Installation

To use this project locally, clone the repository from GitHub:

    git clone git@github.com:thulaneiallen/CSP451-CheckPoint1-Allen.git

Then move into the project folder:

    cd CSP451-CheckPoint1-Allen

No external dependencies are required because this is a basic static website. A web browser is enough to view the project.

## Usage

Open the `index.html` file in a web browser to view the landing page.

The project includes:

- `index.html` for the main page structure
- `style.css` for page styling
- `script.js` for basic JavaScript output
- `VERSION_CONTROL_WRITEUP.md` for the version control explanation
- `about.html` for the feature-branch exercise

Helpful Git commands used in this project include:

    git status
    git add .
    git commit -m "type: message"
    git log --oneline --graph --all --decorate
    git push

## Contributing

This project uses a feature-branch workflow.

To contribute or make changes:

1. Create a new branch from `main`.
2. Make small, focused changes.
3. Commit changes using Conventional Commits.
4. Push the branch to GitHub.
5. Open a pull request for review.
6. Merge the pull request after approval.

Example branch name:

    feature/add-about-page

Example commit messages:

    feat: create basic HTML structure
    docs: enhance README with detailed information
    style: improve page styling

## License

Copyright 2026 Thulanei Allen.

This project was created for CSP451 CheckPoint 1 at Seneca Polytechnic. It is intended for educational use as part of the course assignment.
