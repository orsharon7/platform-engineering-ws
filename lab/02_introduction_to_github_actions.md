# Introduction to GitHub Actions
**Duration:** 20 minutes

GitHub Actions is a powerful feature of GitHub that enables automation of software development workflows directly within your repository. It allows you to build, test, and deploy your code based on events such as pushes, pull requests, or schedule triggers, enhancing your continuous integration and continuous deployment (CI/CD) processes.

## Prerequisites
- A GitHub account
- Basic understanding of GitHub repositories and workflows

## What is GitHub Actions?
GitHub Actions is a CI/CD platform that allows you to automate your build, test, and deployment pipeline. You can create workflows that build and test every pull request to your repository, or deploy merged pull requests to production. GitHub Actions goes beyond just DevOps and lets you run workflows when other events happen in your repository. For example, you can run a workflow to automatically add the appropriate labels whenever someone creates a new issue in your repository. [oai_citation_attribution:6‡GitHub Docs](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions)

Let's explore the core components of GitHub Actions:

### Workflows
A **workflow** is a configurable automated process made up of one or more jobs. Workflows are defined by YAML files stored in the `.github/workflows` directory of your repository. They can be triggered by events, on a schedule, or manually. [oai_citation_attribution:5‡GitHub Docs](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions)

### Events
An **event** is a specific activity in a repository that triggers a workflow run. For example, an activity can originate from GitHub when someone creates a pull request, opens an issue, or pushes a commit to a repository. You can also trigger a workflow to run on a schedule, by posting to a REST API, or manually. [oai_citation_attribution:4‡GitHub Docs](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions)

### Jobs
A **job** is a set of steps in a workflow that is executed on the same runner. Each step is either a shell script that will be executed, or an action that will be run. Steps are executed in order and are dependent on each other. Since each step is executed on the same runner, you can share data from one step to another. [oai_citation_attribution:3‡GitHub Docs](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions)

### Actions
An **action** is a custom application for the GitHub Actions platform that performs a complex but frequently repeated task. Use an action to help reduce the amount of repetitive code that you write in your workflow files. An action can pull your Git repository from GitHub, set up the correct toolchain for your build environment, or set up the authentication to your cloud provider. [oai_citation_attribution:2‡GitHub Docs](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions)

### Runners
A **runner** is a server that runs your workflows when they're triggered. Each runner can run a single job at a time. GitHub provides Linux, Windows, and macOS virtual machines to run your workflows, or you can host your own self-hosted runners in your own data center or cloud infrastructure. [oai_citation_attribution:1‡GitHub Docs](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions)

## Benefits of Using GitHub Actions
- **Automation:** Streamline repetitive tasks such as testing and deployment.
- **Integration:** Seamlessly integrates with GitHub repositories, enhancing the development workflow.
- **Customization:** Create custom workflows tailored to your project's needs.
- **Scalability:** Supports complex workflows with multiple jobs and dependencies.

For more detailed information, refer to the [GitHub Actions documentation](https://docs.github.com/en/actions).

---

## Next Module: [Getting Started with Your Lab](lab/03_getting_started_with_your_lab.md)