# Day 1: What I Learned Today

## **Introduction to AI**
- Learned the basics of AI and its applications.
- Explored how AI can be used in automation and workflows.

## **GitHub Repository**
- Created my first GitHub repository to document my learning journey.
- Learned how to create and commit files using GitHub.

## **n8n Setup**
- Read the [n8n self-hosting guide](https://docs.n8n.io/hosting/).
- Installed Docker on my Mac.
- Installed n8n locally using Docker with the following command:
  ```bash
  docker run -d --name n8n -p 5678:5678 -v ~/.n8n:/home/node/.n8n n8nio/n8n

   ~/.n8n:/home/node/.n8n n8nio/n8n
  
Accessed n8n by opening http://localhost:5678 in my browser.

Course AI Account
Created a Course AI account to explore AI-powered learning.

n8n Basic Tutorial
Read the n8n basic tutorial.

Created my first workflow:
HTTP Request Node: Fetched data from https://randomuser.me/api/.
Code Node: Processed the data to extract name and email.
Write to File Node: Attempted to save the data to a file (still troubleshooting this part).
Challenges Faced
Had issues with the Write to File Node due to folder permissions and Docker volume mapping.
Learned how to troubleshoot Docker errors and adjust folder permissions.

Next Steps
Fix the Write to File Node issue.
Explore more n8n nodes and workflows.
Document my progress as I continue learning.

Resources
n8n Documentation
Docker Installation Guide
GitHub Guides
