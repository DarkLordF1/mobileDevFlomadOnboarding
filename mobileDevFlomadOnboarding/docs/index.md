
# Mobile Developer Onboarding Checklist (Flutter + Firebase)

Welcome to the team! Here's your onboarding checklist to get up to speed with our mobile development workflow using Flutter and Firebase.

---

## 1. Environment Setup
- [ ] Install [Flutter SDK](https://docs.flutter.dev/get-started/install) and add it to your system PATH
- [ ] (Optional) Install [Dart SDK](https://dart.dev/get-dart) separately if needed
- [ ] Set up [Android Studio](https://developer.android.com/studio) or [VS Code](https://code.visualstudio.com/) with Flutter and Dart plugins
- [ ] Configure Android/iOS emulator or physical device
- [ ] Clone the main project repository and run `flutter pub get`
- [ ] Run the project on your emulator or device to verify setup

## 2. Firebase Setup
- [ ] Create or request access to the [Firebase Console](https://console.firebase.google.com/)
- [ ] Download `google-services.json` (for Android) and/or `GoogleService-Info.plist` (for iOS)
- [ ] Place the files in their correct platform directories
- [ ] Install [Firebase CLI](https://firebase.google.com/docs/cli): `npm install -g firebase-tools`
- [ ] Authenticate with Firebase CLI: `firebase login`
- [ ] Initialize or link the Firebase project: `firebase init` (if needed)
- [ ] Ensure setup for:
  - [ ] [Authentication](https://firebase.google.com/docs/auth)
  - [ ] [Firestore Database](https://firebase.google.com/docs/firestore)
  - [ ] [Firebase Storage](https://firebase.google.com/docs/storage)

## 3. Project Knowledge
- [ ] Read the project's `README.md` and any contributing guides
- [ ] Understand the folder structure and architecture
- [ ] Explore the main modules/screens and navigation system
- [ ] Review how authentication works (user flow)
- [ ] Learn our state management approach (e.g., Provider, Riverpod, BLoC)
- [ ] Get familiar with any external packages/libraries
- [ ] Review Firebase integration for each service

## 4. Development Standards
- [ ] Read and follow our code style and naming conventions
- [ ] Follow our Git branching strategy (e.g., feature/, bugfix/)
- [ ] Use our commit style (e.g., Conventional Commits)
- [ ] Understand the pull request review process
- [ ] Learn how to write and run [Flutter tests](https://docs.flutter.dev/cookbook/testing)

## 5. Tools and Accounts
- [ ] Join our GitHub/GitLab repository
- [ ] Request access to:
  - [ ] Firebase Console
  - [ ] Communication tool (Slack/Discord/Teams)
  - [ ] Project management tool (Jira, Trello, etc.)
  - [ ] CI/CD pipeline tool (e.g., GitHub Actions, Codemagic)
- [ ] Set up code formatter: `flutter format .`
- [ ] Install [Flutter Lints](https://pub.dev/packages/flutter_lints)

## 6. Initial Tasks
- [ ] Complete a small starter task or fix a simple bug
- [ ] Push your changes and create a Pull Request
- [ ] Go through the code review process
- [ ] Run and pass all project tests
- [ ] Deploy to staging (if applicable)

## 7. Optional (Recommended)
- [ ] Write a short internal doc explaining a feature or module you learned
- [ ] Contribute to improving documentation or README
- [ ] Attend team syncs or watch the recordings of past ones

---

Happy coding and welcome aboard!
