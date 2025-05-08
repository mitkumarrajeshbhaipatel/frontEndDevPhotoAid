
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

Install Expo CLI (if not installed)

        npm install -g expo-cli
        (This will install Expo CLI globally.)

Verify Expo CLI Installation

        expo --version
        (Check the installed version of Expo CLI)

---

### Detailed Setup ######################################################

### Frontend Project Setup Instructions ##############################

Welcome to the PhotoAid Frontend Project!

Follow these simple steps to set up, run, and manage the project locally:

1. Clone the Repository

        git clone https://github.com/mitkumarrajeshbhaipatel/frontEndDevPhotoAid.git
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

        REACT_NATIVE_APP_API_URL=http://localhost:5000/api
        REACT_NATIVE_APP_FIREBASE_API_KEY=your-firebase-api-key

        Replace the placeholders with your actual configuration.

5. Run the Development Server

        expo start
        This will start the Expo development server.

        The app will be available at http://localhost:19002, or you can scan the QR code with the Expo Go app on your mobile device.

---

### For Testing the Frontend ##########################################
Follow these simple steps to test and run the frontend application:

1. Clean Node Modules (Optional)

        rm -rf node_modules
        npm install
        (This is useful if you're facing dependency issues.)

2. Run the Development Server

        expo start
        The frontend server will start, and the app will be available at http://localhost:19002.

3. Run All Tests (if set up)

        npm test
        This command will run all the tests in the project and show the results.

4. Build the Application for Production

        expo build:android
        # or
        expo build:ios
        This command will build the project for production and create the optimized build files for Android or iOS.

---

### Quick Example (Full Setup) #######################################

In terminal window 1:

        git clone https://github.com/mitkumarrajeshbhaipatel/frontEndDevPhotoAid.git
        cd photoaid-frontend
        npm install
        expo start

In terminal window 2:

        Open the Expo Go app on your mobile device and scan the QR code displayed in the terminal or browser.

        # or

        Open an iOS/Android emulator and run the app using the emulator.

---

### Notes #########################################################

- Make sure Node.js, npm, and Expo CLI are installed on your machine before running any commands.
- Always run `npm install` in the project directory before starting the development server.
- Press `CTRL+C` to stop the development server at any time.
- For building the app on a physical device or emulator, ensure you have either **Android Studio** or **Xcode** installed.
- If you face issues, try running `expo update` to ensure all dependencies are up to date.

✅ Setup complete! You can now develop, test, and explore your PhotoAid frontend application.

================================================
