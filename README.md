### For Frontend Setup ##############################################

Install Node.js (if not installed)

        brew install node
        (You only need to install it once.)

Verify Node.js Installation

        node -v
        (Check the installed version of Node.js)

Install npm (Node Package Manager)

        brew install npm
        (This will install npm along with Node.js)

---

### Detailed Setup ######################################################

### Frontend Project Setup Instructions ##############################

Welcome to the PhotoAid Frontend Project!

Follow these simple steps to set up, run, and manage the project locally:

1. Clone the Repository

        git clone https://github.com/yourusername/photoaid-frontend.git
        This command will clone the frontend repository to your local machine.

2. Navigate to the Project Directory

        cd photoaid-frontend
        This will move you into the cloned project directory.

3. Install Project Dependencies

        npm install
        This will install all the necessary frontend dependencies listed in the package.json file.

4. Set Up Environment Variables

        Create a `.env` file in the root of the project.
        Example:

        REACT_APP_API_URL=http://localhost:5000/api
        REACT_APP_FIREBASE_API_KEY=your-firebase-api-key

        Replace the placeholders with your actual configuration.

5. Run the Development Server

        npm start
        This will start the local development server.

        The app will be available at http://localhost:3000.

---

### For Testing the Frontend ##########################################
Follow these simple steps to test and run the frontend application:

1. Clean Node Modules (Optional)

        rm -rf node_modules
        npm install
        (This is useful if you're facing dependency issues.)

2. Run the Development Server

        npm start
        The frontend server will start, and the app will be available at http://localhost:3000.

3. Run All Tests

        npm test
        This command will run all the tests in the project and show the results.

4. Build the Application for Production

        npm run build
        This command will build the project for production and create the optimized build files in the `build` directory.

---

### Quick Example (Full Setup) #######################################

In terminal window 1:

        git clone https://github.com/yourusername/photoaid-frontend.git
        cd photoaid-frontend
        npm install
        npm start

In terminal window 2:

        Open your browser and go to http://localhost:3000

---

### Notes #########################################################

- Make sure Node.js and npm are installed on your machine before running any commands.
- Always run `npm install` in the project directory before starting the development server.
- Press `CTRL+C` to stop the development server at any time.

✅ Setup complete! You can now develop, test, and explore your PhotoAid frontend application.

================================================
