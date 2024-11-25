A proof-of-concept desktop application using Electron that enables users to execute predefined MongoDB `find` queries and view the results in JSON format. The application will be hosted in a GitHub repository, where the source code will be managed and integrated with a CI/CD pipeline configured through GitHub Actions to automate building and testing processes. The Electron app will establish a connection to a specific MongoDB instance without allowing configurable connection strings, ensuring simplicity and focus on the core functionality of running queries and displaying their outcomes. This project aims to provide hands-on experience with Electron for desktop development, MongoDB integration, and the implementation of automated deployment workflows using GitHub Actions.

Steps to Run
1. npm install
2. On terminal 1, Run node backend/server.js   
3. On terminal 2, Run npx webpack  and then Run npx electron .   