# MERN Stack To-Do App
## Agenda
Building a simple To-Do App with stack tools like Node.js, Express, React, MongoDB, Heroku, GitHub Actions, and Docker.

## Purposeful Tools 
  - Node.js & Express:
    - Backend server development
    - Routing and handling HTTP requests
    - Middleware integration for request processing
    - Interaction with MongoDB using MongoDB Node.js driver
  
  - React:
    - Building user interfaces with reusable components
    - Managing application state using hooks and context API
    - Handling user interactions and events
    - Making asynchronous requests to the backend API
  
  - MongoDB:
    - NoSQL database for storing To-Do items
    - Schema-less design allowing flexibility in data structure
    - CRUD operations (Create, Read, Update, Delete) for managing To-Do items
    - Integration with Node.js using MongoDB Node.js driver or Mongoose ODM

  - Heroku:
    - Deployment of Node.js applications to the cloud
    - Easy scaling of application resources
    - Configuration and management of environment variables
    - Continuous deployment integration with GitHub
  
  - GitHub Actions:
    - Automated workflows for Continuous Integration (CI) and Continuous Deployment (CD)
    - Running tests, linting, and other checks on every commit or pull request
    - Deploying the application to Heroku or other platforms automatically
  
  - Docker:
    - Containerization of the application for consistent development and deployment environments
    - Packaging the application along with its dependencies into a container image
    - Isolating the application from the underlying system dependencies
    - Running the application in various environments consistently, including     
      development, testing, and production

**Step 1: Set Up Development Environment:**

1. **Install Node.js and npm:** [https://nodejs.org](https://nodejs.org)
2. **Personal Choice of IDE:** Visual Studio Code.
3. **Create a project directory:** `mkdir mern-todo && cd mern-todo`

**Step 2: Build the Frontend (React):**

1. **Create React app:** `npx create-react-app client`
2. **Navigate to the client directory:** `cd client`
3. **Install dependencies:** `npm install axios`
4. **Develop React components for UI:** Design screens for displaying, adding, editing, and deleting tasks.
5. **Connect to backend API:** Fetch data from the backend and manage user interactions.

**Step 3: Build the Backend (Node.js, Express):**

1. **Initialize Node.js project:** `npm init -y`
2. **Install dependencies:** `npm install express mongoose cors dotenv`
3. **Create Mongoose models:** Define models for tasks and users (if needed).
4. **Implement API endpoints:** Develop routes for CRUD operations on tasks and user management.
5. **Implement security and authentication:** Secure your API with JWT or similar (optional).

**Step 4: Set Up Database (MongoDB):**

1. **Create a free MongoDB Atlas account:** [https://cloud.mongodb.com](https://cloud.mongodb.com): [https://cloud.mongodb.com](https://cloud.mongodb.com)
2. **Create a database and cluster:** Connect your app to the cluster.
3. **Configure connection string:** Store it securely in an environment variable (e.g., `.env` file).

**Step 5: Deploy to Heroku:**

1. **Create a Heroku account:** [https://signup.heroku.com](https://signup.heroku.com): [https://signup.heroku.com](https://signup.heroku.com)
2. **Install Heroku CLI:** [https://devcenter.heroku.com/articles/heroku-cli](https://devcenter.heroku.com/articles/heroku-cli): [https://devcenter.heroku.com/articles/heroku-cli](https://devcenter.heroku.com/articles/heroku-cli)
3. **Configure Procfile:** Define processes for front-end and back-end servers.
4. **Push code to GitHub:** Host your code in a public or private repository.
5. **Connect Heroku to GitHub:** Link your repository to Heroku app deployment.
6. **Deploy to Heroku:** Push your code to GitHub and watch for automatic deployment by Heroku.

**Step 6: Implement CI/CD with GitHub Actions:**

1. **Create GitHub Actions workflows:** Configure workflows for automatic deployments on push or pull requests.
2. **Build and test stages:** Set up actions to build the front-end, run tests, and deploy to Heroku on successful builds.
3. **Push workflows to your repository:** Share them with your team for automated deployments.

**Step 7: Dockerize the Application:**

1. **Create Dockerfiles:** Write Dockerfiles for front-end and back-end services.
2. **Specify dependencies:** Include required dependencies and build environments in Dockerfiles.
3. **Build and push Docker images:** Build images and push them to a container registry like Docker Hub.
4. **Configure Heroku for Docker:** Update deployment settings to use the Docker images.

**Step 8: Maintenance and Updates:**

1. **Version control:** Use Git to track changes and maintain a clean code history.
2. **Continuous integration:** Ensure builds and tests pass before deployments.
3. **Monitoring and logging:** Monitor app performance and logs for potential issues.
4. **Updates and new features:** Regularly update dependencies and add new features as needed.

**Additional Resources:**

* MERN Stack Tutorial: [https://www.freecodecamp.org/news/learn-the-mern-stack-tutorial/](https://www.freecodecamp.org/news/learn-the-mern-stack-tutorial/): [https://www.freecodecamp.org/news/learn-the-mern-stack-tutorial/](https://www.freecodecamp.org/news/learn-the-mern-stack-tutorial/)
* Heroku Deployment Guide: [https://devcenter.heroku.com/categories/reference](https://devcenter.heroku.com/categories/reference): [https://devcenter.heroku.com/categories/reference](https://devcenter.heroku.com/categories/reference)
* GitHub Actions documentation: [https://docs.github.com/actions](https://docs.github.com/actions): [https://docs.github.com/actions](https://docs.github.com/actions)
* Docker Documentation: [https://docs.docker.com/](https://docs.docker.com/): [https://docs.docker.com/](https://docs.docker.com/)
* MongoDB Atlas Documentation: [https://docs.atlas.mongodb.com/](https://docs.atlas.mongodb.com/): [https://docs.atlas.mongodb.com/](https://docs.atlas.mongodb.com/)


## Prime Resourcess

1. https://medium.com/devops-techable/how-to-install-nvm-node-version-manager-on-macos-with-homebrew-1bc10626181

