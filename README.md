# Java Web App with Remote Development and GitHub Integration

## Project Overview
This project demonstrates building a Java web application using Maven, with remote development on an AWS EC2 instance connected through VS Code. It incorporates version control with Git and GitHub for efficient collaboration and code management.

## Key Features
- Java web app built with Maven
- Remote development environment setup using VS Code connected to EC2 via SSH
- SSH key-based authentication for secure development
- Editing code both through VS Code and terminal editor (nano)
- Git for version control, linked to a GitHub repository
- Use of GitHub personal access tokens for secure push/pull operations

## Technologies Used
- Java 8 (Amazon Corretto)
- Apache Maven
- AWS EC2 and IAM
- VS Code IDE
- Git & GitHub
- Nano text editor for terminal-based editing

## Setup Instructions

1. **AWS Setup**  
   - Create an IAM user with admin permissions for safe AWS usage  
   - Launch and connect to an EC2 instance

2. **Development Environment**  
   - Install Java (Amazon Corretto) and Maven on EC2  
   - Set up VS Code with the Remote - SSH extension for connection  
   - Clone GitHub repository or initialize a new Git repo

3. **Version Control**  
   - Install Git on the EC2 instance  
   - Authenticate with GitHub using a personal access token  
   - Commit and push changes regularly to track project progress  

4. **Editing Code**  
   - Modify Java web app files via VS Code or nano terminal editor  
   - Manage JSP files such as `index.jsp` for dynamic web content  
   - Use Maven commands to build and test the application

## Learnings and Challenges
- Gained hands-on experience with remote development workflows  
- Overcame challenges editing code via nano compared to VS Code IDE  
- Understood GitHub token-based authentication for secure access  
- Built familiarity with Java web app structure and Maven build lifecycle

## Next Steps
This project is part of a DevOps series aimed at building a CI/CD pipeline. Upcoming work will automate testing, building, and deployment to streamline delivery.

---
