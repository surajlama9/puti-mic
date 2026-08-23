
GHBanner


Run and deploy your AI Studio app

This contains everything you need to run your app locally.


View your app in AI Studio: https://ai.studio/apps/2f6c16da-e9ff-4499-bf29-a7d4b75e8593


Run Locally

Prerequisites:  Android Studio



Open Android Studio

Select Open and choose the directory containing this project

Allow Android Studio to fix any incompatibilities as it imports the project.

Create a file named .env in the project directory and set GEMINI_API_KEY in that file to your Gemini API key (see .env.example for an example)

Remove this line from the app's build.gradle.kts file: signingConfig = signingConfigs.getByName("debugConfig")

Run the app on an emulator or physical device

If you have already published your app in AI Studio, please request upload key reset in Google Play Console.

