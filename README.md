# Haknah Privacy Screen

Lightweight Android app starter for Redmi A5 / Android 15 Go.

## What it does
- Displays a simple navy/purple control screen.
- Adds narrow dark strips at the left and right edges using Android's overlay permission.
- Includes ON/OFF controls.
- No network access, analytics, account, API key, or paid service.

## Important limitation
This is a visual edge overlay, **not true side-angle privacy**. Software cannot change the LCD's viewing-angle characteristics. The strips are visible from the front too and may cover small parts of apps.

## Build
Push this project to a GitHub repository. GitHub Actions builds a debug APK on push to `main`, or via Actions > Build Haknah Privacy Screen APK > Run workflow.

The APK appears under the workflow run's Artifacts as `Haknah-Privacy-Screen-debug`.
