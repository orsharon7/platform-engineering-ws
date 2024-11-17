# Getting Started with Your Lab
**Duration:** 15 minutes

Before you can start working on this lab, there are a few essential steps to prepare your environment. Follow the instructions below to ensure you're ready to dive into the lab activities.

---

## Step 1: Open a GitHub Account
1. Visit [GitHub](https://github.com) and sign up for an account if you don’t already have one.
2. Confirm your email address and complete the onboarding process.
3. Ensure you have access to **GitHub Actions**:
   - Go to **Settings** in one of your repositories.
   - Navigate to **Actions** under the repository settings.
   - Ensure that Actions are enabled for your repository (if not, click **Enable Actions**).
   - For organizational accounts, make sure that repository-level Actions permissions are allowed.

---

## Step 2: Install Visual Studio Code
Visual Studio Code (VS Code) is a powerful and lightweight code editor that supports a variety of extensions. To maximize productivity in this lab, we recommend using VS Code.

1. **Download and Install VS Code**:
   - Visit the [Visual Studio Code website](https://code.visualstudio.com/).
   - Download the installer for your operating system and follow the installation instructions.

2. **Install Recommended Extensions**:
   - Open VS Code.
   - Navigate to the **Extensions** view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
   - Search for and install the following extensions:
     - **GitHub Copilot**: Provides AI-powered code suggestions.
     - **GitHub Actions**: Simplifies working with GitHub Actions workflows.
     - **Azure Tools**: Integrates Azure services directly into VS Code.
     - **Docker**: Enables you to work with Docker containers seamlessly (if applicable for your lab).
     - **Prettier**: A code formatter to ensure consistency in your code.
     - **REST Client**: For testing APIs directly within VS Code (if your lab involves API work).

---

## Step 3: Configure Git
To work with GitHub and GitHub Actions effectively, you’ll need Git installed and configured on your system.

1. **Install Git**:
   - Visit the [Git website](https://git-scm.com/) and download the latest version.
   - Follow the installation instructions for your operating system.

2. **Configure Git**:
   - Open a terminal or command prompt.
   - Run the following commands to set your Git username and email:
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"
     ```

3. **Verify Installation**:
   - Run `git --version` in your terminal to ensure Git is installed correctly.

---

## Step 4: Clone the Lab Repository
1. Open your terminal or command prompt.
2. Clone the lab repository to your local machine:
   ```bash
   git clone https://github.com/orsharon7/platform-engineering-ws.git
   ```
3. Navigate to the repository folder:
    ```bash
   cd platform-engineering-ws
   ```