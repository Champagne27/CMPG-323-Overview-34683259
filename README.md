![2000](https://github.com/Champagne27/CMPG-323-Overview-34683259/blob/main/2000.jpeg?raw=true)
# CMPG-323-Overview-34683259
✨ Hi, I'm Joel. Let's bring ideas to life in CMPG 323! ✨

Project 1 will be created on this repository named CMPG-323-Overview - <34683259>

# Project Repositories to be created for each project 
- CMPG-323-Overview Project 1 - <34683259> 
- CMPG 323 Project 2 - <34683259>
- CMPG 323 Project 3 - <34683259>
- CMPG 323 Project 4 - <34683259>
- CMPG 323 Project 5 - <34683259>

# Documentation
![Lean Technical Documentation Template]
# Branching Strategy to be used within each project 📁

## Why is branching important? 🤔
Branching is a fundamental and powerful feature of modern version control sytems that enables more efficient, collaborative, and manageable software development workflows.

## Branching strategies to be used 💡
We employ a feature-based approach to managing code changes effectively. This strategy enables parallel development, where multiple developers can work on different features or bug fixes simultaneously without interfering with each other's work. This approach helps maintain code quality and minimize conflicts that may arise during the development process.

## Branch types
1. **Main Branch:** The `main` branch contains the production-ready code. All changes to this branch are thoroughly tested and reviewed. 
   
2. **Feature Branches:** For each new feature, bug fix, or enhancement, create a new branch based on `main`. Use descriptive names that reflect the feature or issue being addressed (e.g., `feature/user-authentication`, `bugfix/data-validation`).

3. **Pull Requests:** Once your feature is complete and ready for review, initiate a pull request from your feature branch to main. This process enables code review, discussion, and testing to take place before the final merge.

## Workflow Summary
1. Creating a new branch for feature or bug fix:
   - Ensure you are on the develop branch:
     ```bash
     git checkout main
     
    - Create a new branch for feature or bug fix
      ```bash
      git checkout -b feature/my-new-feature
     
   -  Start working on feature or bug fix
  
2. Regularly commit changes to the feature branch:
   - As you work on your feature or bug fix, regularly stage your changes:
     ```bash
     git add .    
   -  Commit your changes with a descriptive message:
      ```bash
      git commit -m "Implement feature: your-feature-name"
     
   - Repeat steps 1 and 2 as you continue to work on your feature or bug fix.
3. Push your changes to the remote repository
   - When you are ready to share your work or want to back up your changes, push your feature or bug fix branch to the 
     remote repository:
     ```bash
      git push origin feature/my-feature-name

# Project Management with .gitignore file to be used within each project 📁
In this project, we utilize a .gitignore file to specify which files and directories Git should ignore, ensuring that only the essential code and resources are kept in the repository. This approach helps maintain a clean and organized repository, reduces unnecessary clutter, and enhances collaboration.

## Why Use a .gitignore? 🤔
During development, projects often generate files and directories automatically, contain sensitive information, or are irrelevant to version control. It's important for Git to exclude these files. The .gitignore file allows us to define patterns for files and directories that should be ignored by Git.

# Storage of credentials and sensitive information ℹ️
The security of our code and user data is of the utmost importance in these projects. To ensure the safe storage and management of credentials and sensitive information, we adhere to the following best practices and rules:

## Rules 📗
- Utilize environment variables to securely store sensitive information, including API keys, passwords, and tokens. This method keeps them separate from the codebase and reduces the risk of unintentional exposure.
   
- Whenever possible, encrypt sensitive data before storing it. This provides an additional layer of security, even if the data is accessed.

- Sensitive data should be kept in configuration files, but it's important to ensure that these files are not tracked by version control.

## Storage of credentials 🔐
- If using environment variables is not feasible, create a separate configuration file and ensure that this file is excluded from being committed by adding it to your `.gitignore` file.
  
- If configuration files need to be included in version control, use placeholders or dummy values instead of actual sensitive data. Include instructions for filling in these files with the necessary information.

## Sensitive information 🔒
To prevent sensitive information from being accidentally committed to version control, we use a `.gitignore` file to exclude files that contain such data. This includes configuration files, secret files, and environment-specific files.

We highly recommend reviewing and updating your project's .gitignore file to ensure that sensitive data remains secure. 
