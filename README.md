# Chat Application with React and ChatEngine.io

This project is a real-time chat application built using React.js and ChatEngine.io. It allows users to:

* Engage in real-time chat conversations
* Manage users (add, remove)
* Save chat history
* Utilize a login system for user authentication

## Prerequisites

* Node.js and npm (or yarn) installed on your system. You can download them from [Node.js](https://nodejs.org/en).

## Getting Started

1. **Clone the Repository:**

```bash
git clone <repository-url>
```

Replace `<repository-url>` with the URL of your Git repository.

2. **Navigate to Frontend Directory:**

```bash
cd frontend
```

3. **Install Dependencies:**

```bash
npm install
```

4. **Create `.env.local` File:**

   - Create a file named `.env.local` in the `frontend` directory.
   - Add the following line to the file, replacing `your-project-id` with your actual ChatEngine.io project ID:

     ```
     VITE_CHAT_ENGINE_PROJECT_ID=your-project-id
     ```

   **Important:**

     - **Do not** commit the `.env.local` file to version control (e.g., Git). This file contains sensitive information.

5. **Run the Application:**

```bash
npm run dev
```

This command starts the application in development mode.

6. **Access the Application:**

   - Open your web browser and navigate to http://localhost:3000 to access the chat application.

## Obtaining a ChatEngine.io API Key

1. Visit ChatEngine.io (https://chatengine.io/).
2. Create an account or sign in if you already have one.
3. Create a new project.
4. Once your project is created, navigate to the project settings and copy your Project ID.
5. Paste the copied Project ID into the `VITE_CHAT_ENGINE_PROJECT_ID` variable in your `.env.local` file.

## Additional Notes

- This project was inspired by a tutorial that covers setting up a Python web-server, connecting to ChatEngine.io for real-time chat, using REST APIs, JavaScript, and websockets. 
- For further reference on ChatEngine.io and API keys, visit their website (https://chatengine.io/).

## Customization

- Feel free to customize this README to include details specific to your project implementation, such as additional features or usage instructions.
- Consider adding screenshots or visuals to enhance the README.
```
