# Container Invoice App

A cross-platform Invoice Generator for Logistics and Shipping containers.

## Prerequisites

1. **Install Node.js** (LTS version) from [nodejs.org](https://nodejs.org/).

### For Windows Build:
Standard setup is sufficient.

### For Android Build:
1. Install **Android Studio**.
2. Open Android Studio and install the **Android SDK**.
3. Set up an Environment Variable `JAVA_HOME` pointing to your JDK location (usually bundled with Android Studio).

## Installation & Running

1. Clone or download this repository.
2. Open a terminal/Command Prompt inside the folder `container-invoice-app`.
3. Install dependencies:
   ```bash
   npm install
How to Build
Option A: Windows Application (.exe)
Run the following command to create the installer in the dist folder:
bashDownloadCopy codenpm run dist-win
Option B: Android APK

1. 
Initialize Android Studio Project:
bashDownloadCopy codenpm run dist-android
(Note: This command will open Android Studio for the first time if the folder isn't created).

2. 
Build APK:

Once Android Studio opens, wait for Gradle to finish syncing.
Go to the top menu: Build > Build Bundle(s) / APK(s) > Build APK(s).
The APK will be located in android/app/build/outputs/apk/debug/.



Usage

* Fill in the form fields.
* Click "Print / PDF" to save or print.
* Use "Regenerate Signature" for new unique digital signatures.


---

### 6. How to Submit to GitHub

1.  **Initialize Git:**
    Open your terminal in the folder and run:
    ```bash
    git init
    git add .
    git commit -m "Initial release of Container Invoice App"
    ```

2.  **Push to GitHub:**
    *   Go to GitHub.com and create a new repository (e.g., named `container-invoice-app`).
    *   Run the commands GitHub provides:
    ```bash
    git remote add origin https://github.com/YOUR_USERNAME/container-invoice-app.git
    git branch -M main
    git push -u origin main
    ```

3.  **Releases (To share files):**
    *   Once you have built the `.exe` (inside the `dist` folder) or the `.apk` manually, go to the **"Releases"** section on your GitHub repository.
    *   Click **"Create a new release"**.
    *   Tag it `v1.0.0`.
    *   Drag and drop your `.exe` or `.apk` file there so users can download it directly without compiling it themselves.
