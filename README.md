Email Validation Application
This project is a simple, client-side email validation application using a combination of HTML, CSS, and JavaScript. It provides real-time feedback to the user as they type, indicating whether the entered email address is in a valid format.

🚀 Features
Real-time Validation: Provides immediate visual feedback (check or exclamation icon) as the user types.

User-Friendly Interface: The form is styled with a clean and modern design.

Client-Side Logic: All validation logic runs directly in the browser, making it fast and responsive.

🛠️ Technologies Used
HTML: Structures the web page and the input form.

CSS: Styles the application, including a custom background and a container with shadow effects.

JavaScript: Handles the core validation logic and dynamic DOM manipulation.

🌐 Azure Deployment
This project is configured for continuous deployment using Azure DevOps Pipelines to an Azure Web App.

Azure Web App Service
The application is hosted on an Azure Web App, a fully managed platform for building, deploying, and scaling web apps. This service simplifies the deployment process, allowing for easy updates and automatic scaling.

Azure DevOps CI/CD Pipeline
The azure-pipelines.yml file in this repository defines an automated CI/CD pipeline that handles the entire deployment process. The pipeline has two main stages:

Build Stage: This stage prepares the application files for deployment. It lists the files in the source directory and publishes them as an artifact, ensuring all necessary code is packaged correctly.

Deploy Stage: This stage takes the build artifact and deploys it to the designated Azure Web App. The pipeline is set up to deploy to a specific appName and azureSubscription, ensuring a seamless and repeatable deployment process every time a change is pushed to the main branch.

How the Pipeline Works
A developer commits and pushes code to the main branch.

Azure DevOps detects the new commit and automatically triggers the pipeline.

The Build Stage runs, collecting all the source files.

The Deploy Stage begins, taking the prepared files and deploying them to the Azure Web App.

The new version of the application becomes live on the web app.

This setup ensures that any change to the codebase is quickly and reliably deployed to the live environment, following a best-practice DevOps workflow.

📂 Project Structure
index.html: The main HTML file containing the form structure.

style.css: The CSS file for styling the application.

script.js: The JavaScript file with the email validation logic.

azure-pipelines.yml: The YAML file for the CI/CD pipeline.

<img width="950" height="470" alt="client side email validation" src="https://github.com/user-attachments/assets/ffbb7b72-b8cd-4d8d-a97c-371075a355d7" />


📝 Getting Started
For Local Development
Clone the repository:

Bash

git clone https://github.com/your-username/your-repo.git
cd your-repo
Open the index.html file in your web browser to view the application.
