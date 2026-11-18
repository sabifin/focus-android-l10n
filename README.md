# AI Coin Hunter — Android prototype

Starter Android project for an on-device reward-indicator monitoring prototype.

## Build APK with GitHub Actions
1. Create a **private** GitHub repository.
2. Upload all files and folders from this project to the repository root.
3. Open the **Actions** tab and enable workflows if GitHub asks.
4. Run **Build Android APK** using **Run workflow**, or push a commit to `main`.
5. When the workflow finishes, open its run and download the `ai-coin-hunter-debug` artifact.
6. Extract the ZIP and install `app-debug.apk` on your Android phone.

## Current scope
- Basic Android dashboard only.
- No TikTok login, password collection, screen capture, accessibility automation, or coin-claim automation.
- Future screen monitoring must use Android's user-approved MediaProjection permission and respect the platform's rules.
