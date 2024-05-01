# Project Frontend-LKS-Networking

This project is a React JS implementation integrated with the OpenAI API, focusing on developing an attractive and responsive user interface. By using React JS as the frontend framework, this project allows users to interact with OpenAI services through a user-friendly interface.

## Getting Started

### Prerequisites

- <a href="https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-debian-10">Installing Node.js with version >= 16</a>
- <a href="https://git-scm.com/book/en/v2/Getting-Started-Installing-Git">Installing Git for Linux</a>

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/LuckyIndraEfendi/Chat-AI-Frontend-LKS.git
   ```
2. Navigate to the directory where the project is located:
   ```sh
   cd your_project
   ```
3. Install dependencies:

   ```sh
   npm install
   ```

## Usage

1. Before running the application, create a .env file. You can use nano or echo to insert the environment variables. For example, you can manually create the file using touch:

   ```sh
   touch .env
   ```

2. For .env `VITE_BACKEND_BASE_URL` must be filled with the URL of the backend, for example if the server is running on port 5000, Make an example like this
   ```sh
   VITE_BACKEND_BASE_URL="http://your-ip-address-backend:port"
   ```
3. If so, you can immediately start the service in development mode by running a command like this

   ```sh
   npm run dev
   ```

4. When the browser has displayed the ui display of the frontend and it is running well, both the login, registration, and interaction features with the AI. then you can directly build the project by running commands like thisHere is an example .env file within this project. By default, the project will run on port 8080. You can customize your port settings with another port. For example:

   ```sh
   npm run build

   ```

5. Running Project in the preview mode

   ```sh
   npm run preview
   ```

## Run Apps with PM2

1. Install PM2 library

   ```sh
   npm install -g pm2
   ```

2. Start Project PM2

   ```sh
   npm run start:prod
   ```

3. Stop Project PM2

   ```sh
   npm run stop:prod
   ```

4. Now your Project is running on PM2 without docker

   ```sh
   http://your-ip-address:port
   ```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## License

Distributed under the MIT License. See `LICENSE` for more information.
