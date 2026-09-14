Workflow 1: Run JavaScript inside GitHub Actions and call the GitHub API.

Workflow 2: Break the JavaScript work into separate steps, then use if: to conditionally execute a step.

Workflow 3: Check out the repository and use the Node.js runtime available inside github-script to read a file and use its contents in an API call.