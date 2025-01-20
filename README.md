# Health Chatbot - React Project

A healthcare chatbot application built with React. This guide will help you set up and run the project.

## Step 1: Install Required Software

1. **Install Node.js and npm:**
   - Go to [Node.js website](https://nodejs.org/)
   - Download the "LTS" (Long Term Support) version
   - Run the installer and follow the installation wizard
   - Verify installation by opening terminal/command prompt and typing:
     ```
     node --version
     npm --version
     ```
   Both commands should display version numbers if installed correctly.

## Step 2: Clone and Set Up the Project

1. **Open your terminal/command prompt**
   - Windows: Press `Windows + R`, type `cmd`, and press Enter
   - Mac: Press `Command + Space`, type `terminal`, and press Enter

2. **Clone the repository:**
   ```bash
   git clone https://github.com/parthiv1499/health-chatbot.git
   ```

3. **Navigate into the project directory:**
   ```bash
   cd health-chatbot
   ```

4. **Install dependencies:**
   ```bash
   npm install
   ```
   This may take a few minutes to complete.

## Step 3: Run the Project

1. **Start the development server:**
   ```bash
   npm start
   ```
   This will automatically open http://localhost:3000 in your browser.

2. **View the application:**
   - The health chatbot interface will appear in your browser
   - The page will automatically reload when you make changes
   - Check the terminal for any error messages

## Troubleshooting Common Issues

1. **Git not found:**
   - Download and install Git from [git-scm.com](https://git-scm.com/)
   - Restart your terminal after installation

2. **Node modules installation fails:**
   - Try clearing npm cache:
     ```bash
     npm cache clean --force
     ```
   - Then run installation again:
     ```bash
     npm install
     ```

3. **Port 3000 already in use:**
   - Press 'Y' when prompted to use a different port
   - Or kill the process using port 3000 and try again

## Project Structure

```
health-chatbot/
  ├── node_modules/    (Dependencies)
  ├── public/          (Static files)
  ├── src/             (Source code)
  ├── package.json     (Project configuration)
  └── README.md        (Documentation)
```

## Available Scripts

### `npm start`
- Starts the development server
- Opens http://localhost:3000 in your browser
- Auto-reloads when you save changes

### `npm test`
- Launches the test runner
- Watches for test file changes

### `npm run build`
- Creates a production-ready build in the `build` folder
- Optimizes the build for best performance

## Need Help?

If you encounter any issues:
1. Check the console for error messages
2. Make sure all prerequisites are installed correctly
3. Try removing `node_modules` folder and `package-lock.json` file, then run `npm install` again
4. Create an issue on the [project repository](https://github.com/parthiv1499/health-chatbot/issues)

## Contributing

Feel free to fork the repository and submit pull requests for any improvements!
