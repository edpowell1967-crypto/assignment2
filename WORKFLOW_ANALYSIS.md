Workflow Analysis

1\. What triggers this workflow to run?

The workflow runs whenever code is pushed to the main branch.



2\. What are the four main steps this workflow performs?

Checkout Code

Validate HTML

Configure GitHub Pages

Deploy to GitHub Pages

3\. What does the "Checkout code" step do and why is it necessary?

The checkout step downloads the repository files into the GitHub Actions runner so that the workflow can access and validate the website files.



4\. What is the purpose of the environment configuration?

The environment configuration prepares GitHub Pages and deployment settings so the website can be published correctly.



5\. How does this automated deployment improve reliability compared to manual deployment?

Automated deployment ensures validation checks are performed consistently before deployment, reducing human errors thereby improving reliability.



6\. What would happen if you pushed code to a different branch (not main)?

The deployment workflow would not run because it is configured to trigger only when code is pushed to the main branch.

