# Biometric Authentication Project

This project implements a secure and user-friendly biometric authentication system using Flutter. It allows users to quickly and safely log in using their device's built-in biometric capabilities, such as fingerprint or facial recognition.

## Key Features Implemented

* **Smart Authentication:** Utilizes device-native biometric sensors (fingerprint and facial recognition) for secure access.
* **Quick Login:** Enables instant authentication, providing a seamless user experience without the need for traditional password entry.
* **Cross-Platform Compatibility:** Designed to work seamlessly across both iOS and Android platforms, offering a consistent experience.
* **Enhanced User Privacy:** Ensures that biometric data is processed and stored securely and locally on the device, adhering to privacy best practices.

## How to Set Up the Project

Follow these steps to get the project up and running on your local machine:

1.  **Clone the Repository:**
    Open your terminal or command prompt and run:
    ```bash
    git clone https://github.com/def-Siddharth-Mishra/auth_biometric.git
    ```
2.  **Navigate to the Project Directory:**
    ```bash
    cd auth_biometric
    ```
3.  **Install Dependencies:**
    Fetch all the necessary Flutter packages:
    ```bash
    flutter pub get
    ```
4.  **Connect a Device or Start an Emulator:**
    Ensure you have an Android emulator, iOS simulator, or a physical device connected. You can list available devices using:
    ```bash
    flutter devices
    ```
5.  **Run the Application:**
    Execute the application on your chosen device:
    ```bash
    flutter run
    ```
    This will compile and launch the app. If you encounter issues with biometric authentication not being available, ensure your device/emulator has biometric hardware enabled and configured.

## Limitations or Assumptions Made

* **Device Biometric Support:** It is assumed that the target device has biometric hardware (fingerprint sensor, Face ID, etc.) and that biometrics are enabled and configured by the user. The application will gracefully handle cases where biometrics are not available or not set up.
* **Local Authentication Only:** This implementation focuses solely on local device authentication using biometrics. It does not include integration with a remote server or a backend authentication system.
* **Basic UI:** The user interface is kept minimal to highlight the core biometric authentication functionality. Further UI enhancements would be required for a production-ready application.
* **No Fallback Methods Implemented (e.g., PIN/Password):** For simplicity, this version does not include alternative authentication methods like PIN or password fallback in case biometric authentication fails or is not preferred.
