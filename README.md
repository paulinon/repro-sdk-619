# repro-sdk-619

## Steps to reproduce:

1. Add the Firebase Auth SDK and your google-services.json file
2. Build the app on an Android device
3. Tap "Sign In With Email" and notice <i>Email Verified: False</i> in the logs
4. Wait for verification email then verify user
5. Tap "Reload User" and notice <i>Email Verified: True</i> in the logs
