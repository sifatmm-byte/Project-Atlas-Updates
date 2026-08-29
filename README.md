# Project Atlas Updates

Public, read-only update channel for the Project Atlas Android app.

This repository intentionally contains **no Atlas source code, credentials, private data, or model files**. It is only used to publish a compiled Atlas APK plus `update.json` metadata so the installed app can check for and verify updates without storing GitHub credentials on the phone.

Atlas verifies the manifest SHA-256, package name, version code, and signing certificate before handing an APK to Android's package installer. Android still requires the user to approve the final installation.
