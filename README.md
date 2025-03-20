# 7 Day DevOps Challenge: NextWork Web Project

## Overview
This project builds a CI/CD pipeline for a web application running on an AWS EC2 instance. It demonstrates using Git for version control, integrating with GitHub via Personal Access Tokens, and automating code deployment.

## Features
- **Version Control:** Manage code changes with Git.
- **Remote Repository:** Sync code with GitHub.
- **Secure Auth:** Use Personal Access Tokens for GitHub authentication.
- **Remote Editing:** Edit code on EC2 via VSCode.
- **CI/CD Pipeline:** Automate build and deployment steps.

## Setup & Installation

1. **Prerequisites:**
   - AWS EC2 instance with Git installed.
   - VSCode with the Remote-SSH extension.
   - A GitHub account.

2. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/nextwork-web-project.git
   cd nextwork-web-project
   ```

3. **Configure Git:**

   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

4. **Connect to GitHub:**
   - Generate a Personal Access Token on GitHub.
   - Add the remote repository:

     ```bash
     git remote add origin https://github.com/yourusername/nextwork-web-project.git
     ```

## Usage

1. **Edit Files:**
   - Open the project in VSCode.
   - Modify files (for example, update `index.jsp` with personalized content).

2. **Stage, Commit, and Push Changes:**

   ```bash
   git add .
   git commit -m "Describe your changes here"
   git push -u origin main
   ```

3. **Review History:**
   - To view pending changes, run:
     
     ```bash
     git diff --staged
     ```
     
   - To view commit history, run:
     
     ```bash
     git log
     ```

## CI/CD Pipeline
This project is part of a 7-day challenge that gradually builds a complete CI/CD pipeline. Future updates will add testing and automated deployment.

## Troubleshooting
- **Authentication:** Use a Personal Access Token instead of your password.
- **No Updates on GitHub:** Ensure that you have committed and pushed your changes.
- **Terminal Issues:** Press `q` to exit pager views if the terminal seems stuck.

## Contributing
Contributions are welcome! Fork the repository and submit pull requests with improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
Thanks to the NextWork community and all contributors for their support during the 7 Day DevOps Challenge.