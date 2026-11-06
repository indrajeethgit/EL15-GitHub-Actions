# VCS Unit 3 – EL 15: GitHub Actions

## 1. Objective
To learn how to create and execute basic GitHub Actions workflows and automate tasks using push events.

## 2. Introduction
GitHub Actions is an automation platform provided by GitHub that allows developers to automate tasks such as testing, building, and deploying applications directly from their repositories.

## 3. Tools and Technologies Used
- Git
- GitHub
- GitHub Actions
- YAML
- Visual Studio Code

## 4. Implementation

### Step 1: Repository Creation
Created a new GitHub repository named `EL15-GitHub-Actions`.

### Step 2: Folder Structure
Created the following folder structure inside the repository:

```text
.github/
    workflows/
        main.yml
README.md
```

### Step 3: Workflow Configuration
Created a YAML workflow file named `main.yml` inside `.github/workflows/`.

### Step 4: Workflow Execution
Configured the workflow to trigger automatically whenever a push event occurs.

### Step 5: Output Verification
Verified the workflow execution through the Actions tab in GitHub.

## 5. Workflow Output

The workflow successfully executed the following command:

```bash
echo "Hello from GitHub Actions!"
```

**Expected Output:**

```text
Hello from GitHub Actions!
```

## 6. Learning Outcomes
- Learned to create and configure GitHub Actions workflows.
- Understood how to trigger workflows using push events.
- Learned the basic structure and indentation of YAML files.
- Understood how to monitor workflow execution through the Actions tab.
- Learned the fundamentals of automation and Continuous Integration.

## 7. Conclusion
Successfully created and executed a basic GitHub Actions workflow. The workflow was automatically triggered by a push event, and its execution was verified through the GitHub Actions tab.