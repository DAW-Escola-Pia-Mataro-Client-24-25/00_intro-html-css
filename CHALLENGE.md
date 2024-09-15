### CHALLENGE.md

# Introduction

Welcome to the **HTML Semantics and CSS Foundations** challenge!

In this exercise, you will learn to apply semantic HTML and basic CSS design principles to create a simple web interface. Additionally, you will be introduced to fundamental concepts of **Source Version Control** using Git and GitHub and **Continuous Integration/Continuous Deployment (CI/CD)** using Netlify.

This challenge is designed for you to practice core web development concepts while also getting hands-on experience with industry-standard tools.

By the end of this challenge, you will have:

- Created a basic HTML/CSS layout following semantic best practices.
- Set up a Git repository to manage your source code.
- Deployed your project on Netlify to make it publicly accessible.

# Source Version Control

### Git and GitHub Setup

To track and manage your project files efficiently, we will use **Git** for version control and **GitHub** as a remote repository. Follow these steps:

1. **Create a GitHub Repository**:

   - Log in to your GitHub account (or create one if you don't have it).
   - Create a new repository named **00_html-semantics**.
   - Do not initialize the repository with a README, `.gitignore`, or any license.

2. **Set Up Local Environment**:

   - On your local machine, open a terminal/command line.
   - Navigate to your working directory where you want to create the project.

   ```bash
   mkdir client-side-module
   cd client-side-module
   ```

3. **Clone the Remote Repository**:

   - Clone the remote repository to your local machine inside the `client-side-module` directory:

   ```bash
   git clone https://github.com/your-username/00_html-semantics.git
   ```

4. **Verify Your Setup**:

   - Move into the cloned repository directory:

   ```bash
   cd 00_html-semantics
   ```

   - Ensure that you are inside the repository by running:

   ```bash
   git status
   ```

   You should see that you are on the `main` branch with no changes made yet.

5. **Create a New Branch**:

   - Create a new branch called `develop` from the `main` branch where you will implement the challenge.

   ```bash
   git checkout -b develop
   ```

   Now you are on the `develop` branch. All the challenge work should be done in this branch.

6. **Push `develop` Branch to GitHub**:

   - Push the `develop` branch to the remote repository so it can be tracked:

   ```bash
   git push -u origin develop
   ```

7. **Complete the Challenge in the `develop` Branch**:

   - Implement the challenge by adding the required `index.html`, `style.css`, and `sanitize.css` files in the `develop` branch.
   - Use Git to track your changes by running:

   ```bash
   git add .
   git commit -m "Add challenge files"
   ```

   - Push the changes to the `develop` branch on GitHub:

   ```bash
   git push
   ```

8. **Create a Pull Request**:

   - After finishing the challenge, go to your repository on GitHub.
   - You will see an option to create a pull request (PR) for merging `develop` into `main`.
   - Click on **Compare & pull request** and provide a meaningful description for the PR.
   - Make sure to review your code and ensure everything is correct before submitting the PR.

9. **Merge via Pull Request**:
   - Once the pull request is created, the changes in the `develop` branch can be reviewed.
   - After the review, you can **merge** the `develop` branch into `main` using the **Merge pull request** button.
   - Ensure no direct commits are made to `main`. All updates must go through the pull request process from `develop` to `main`.

By using the **branching model** and pull requests, you ensure a clean and collaborative workflow for development. This also prepares you for working in team-based environments where code reviews and feature branches are common practice.
warning. PR can be only merged into main under teacher approve

# Challenge

### Requirements

In this challenge, you will recreate the HTML and CSS interface based on the code provided in previous examples. Follow the steps below to complete your task:

1. **Create `index.html` File**:

   - In the `00_html-semantics` folder, create an `index.html` file.
   - The `index.html` file must contain semantic HTML..
   - Include a form in the main section, as demonstrated in the previous example, and include appropriate semantic tags.

2. **Create `style.css` File**:

   - Create a `style.css` file in the same directory.
   - The CSS should style your HTML page based on the previous example:
     - Ensure that the content is centered.
     - Set a 100% wide header.
     - Place sections as described (side-by-side).
     - Use a simple chromatic palette for design.

3. **Create `sanitize.css` File**:

   - Create a `sanitize.css` file, based on the provided example.
   - This file will help normalize styling across different browsers.

4. **Ensure Functionality**:

   - The final interface must look as close as possible to the example provided earlier. Ensure that the layout and form elements are properly styled and functional.

5. **Test Your HTML/CSS**:
   - Open the `index.html` file in your browser to check if everything is displayed correctly.

# CI/CD

### Deploy the Project Using Netlify

Now that your project is ready, it's time to deploy it online using **Netlify**. Follow these steps:

1. **Create a Netlify Account**:

   - If you don't have a Netlify account, sign up for one at [https://www.netlify.com](https://www.netlify.com).

2. **Link GitHub Repository to Netlify**:

   - In the Netlify dashboard, click on **Add New Site** and choose **Import an existing project**.
   - Select **GitHub** as the source and authenticate your GitHub account.
   - Find and select your `00_html-semantics` repository.

3. **Configure Deployment Settings**:

   - In the build settings, you can leave the default values as Netlify will auto-detect this as a static site.
   - No additional build command is needed for this simple project.

4. **Deploy the Site**:

   - Click on **Deploy Site**.
   - After the deployment process completes, your site will be live with a Netlify-provided URL.

5. **Customizing the URL (Optional)**:
   - You can change the default Netlify subdomain to a custom one by going to the **Domain Settings** in your Netlify dashboard.

# Generative AI

### Using AI Assistance

During the challenge, you can use Generative AI tools, including this assistant, to help with the challenge. Feel free to:

- Request explanations of any piece of code.
- Ask for clarifications on HTML, CSS, Git, or Netlify deployment steps.

AI should be used to enhance your learning, so while it can generate code or explain concepts, ensure you understand the processes to fully benefit from the challenge.

Good luck! 🚀
