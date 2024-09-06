# Android Studio Installation Guide (Windows)

For Quick Setup follow step 1,2 and 4 and you are done


## 1. Download and Install Android Studio
- **Visit the official website**: Go to the [Android Studio download page](https://developer.android.com/studio/install).
- **Download the Installer**: Click on the "Download Android Studio" button and accept the terms and conditions to start the download.
- **Run the Installer**:
  - Open the downloaded file and follow the on-screen instructions.
  - During installation, ensure that all components (Android SDK, SDK tools, and Virtual Device) are selected.
- **Launch Android Studio**: After installation, open Android Studio.

## 2. Set Up Android Studio
- **First-Time Setup**: On the first launch, Android Studio will guide you through the setup process, including downloading the necessary SDK components.
- **Choose Standard Settings**: Opt for the standard installation unless you have specific preferences.
- **Install SDK and Tools**: Android Studio will automatically download the Android SDK and other required tools.

## 3. Create a New Android Project
- **Start a New Project**:
  - On the welcome screen, click on **New Project**.
  - Select the **Phone and Tablet** template, then choose **Empty Activity**.
  - Set up your project details (name, package name, save location, language, and API level).
  - Click **Finish** to create the new project.
- **Explore the Project**: Once the project is created, you'll see the `MainActivity.kt` and `activity_main.xml` files. Modify these to build your app.

## 4. Clone an Existing Android Project
- **Clone via Git**:
  - On the welcome screen, click on **Get from VCS**.
  - Enter the repository URL (from GitHub or other VCS platforms).
  - Click **Clone**, and Android Studio will download and set up the project.
- **Sync and Build**: Once cloned, sync the project with Gradle to ensure all dependencies are resolved.

## 5. Run the App
- **Set up an Emulator**:
  - Open **AVD Manager** to create a virtual device (emulator) for testing.
  - Select a device and system image (make sure it matches your project's API level).
  - Launch the emulator.
- **Run the App**:
  - Click the green **Run** button or press `Shift + F10` to build and run the app on the emulator.

## Reference
For more detailed instructions, check the [official Android Studio installation guide](https://developer.android.com/studio/install).
