Task 0: Mobile Development Environment Setup
Setup Process

    Installed Node.js LTS (v18.x):
        Verified with: node -v → Output: v18.x.x

    Installed npm (Node Package Manager):
        Verified with: npm -v → Output: 8.x.x or higher

    Installed VS Code as the primary code editor.

    Installed Expo Go on a physical Android device:
        Downloaded from the Google Play Store
        Signed in with an Expo account.

    Transitioned from legacy Expo CLI to modern CLI:
        Removed legacy expo-cli due to compatibility issues with Node.js 17+.
        Confirmed removal using which expo.
        Used npx create-expo-app for future app scaffolding.

Challenges Faced

    Encountered deprecated warnings during expo-cli installation (e.g., uuid@3.4.0, rimraf@2.x, etc.).
    Compatibility Issue: expo-cli indicated that Node.js v17+ is unsupported.
        Solution: Uninstalled expo-cli globally and switched to the modern Expo CLI using npx.
    Cleanup: Verified that the expo binary was removed from the system PATH using which expo.