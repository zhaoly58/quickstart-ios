# Firebase AI Quickstart

This sample demonstrates how to make calls to the Gemini API via Firebase directly
from your app, rather than server-side, using the
[Vertex AI for Firebase SDK](https://firebase.google.com/docs/vertex-ai/get-started?platform=ios).

## Getting Started

### Clone and open the sample project

1. Clone this repo.
1. Change into the `firebaseai` directory.
1. Open `FirebaseAIExample.xcodeproj` using Xcode.

```bash
git clone https://github.com/firebase/quickstart-ios.git
cd quickstart-ios/firebaseai
open FirebaseAIExample.xcodeproj
```

### Connect the sample to your Firebase project

To have a functional application, you will need to connect the Firebase AI
sample app to your Firebase project (or create a new project):

1. Follow the instructions in
   [Set up a Firebase project and connect your app to Firebase](https://firebase.google.com/docs/vertex-ai/get-started?platform=ios#set-up-firebase).
2. Add an iOS+ app to your project. Make sure the `Bundle Identifier` you set
   matches the one in the sample.
     - The default bundle ID is `com.google.firebase.quickstart.FirebaseAIExample`
3. Download the `GoogleService-Info.plist` for the app when prompted and save
   it to the `firebaseai` directory.

You should now be able to build and run the sample!

### Request logging

The `-FIRDebugEnabled` option is set as a command line argument in the build
scheme to log server requests to the console. Remove the option to turn off the
logging.

## Documentation

To learn more about the Firebase AI SDK, check out the
[documentation](https://firebase.google.com/docs/vertex-ai).

## Support

- [GitHub Issue](https://github.com/firebase/firebase-ios-sdk/issues/new/choose)
  - File an issue in the `firebase-ios-sdk` repo, choosing the Firebase AI product.
- [Firebase Support](https://firebase.google.com/support/)
