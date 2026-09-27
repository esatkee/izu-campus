# İZÜ Campus

A student-built campus information app in Flutter.

Course schedules, exam results, attendance and transcripts, with an HTTP service layer for student and course data.

<details>
<summary>Setup & technical notes</summary>

### Screens and components

- Student information and course details.
- Course and exam schedules, results and attendance views.
- Transcript view and a transcript calculation widget.
- Course materials, application forms and emergency contact information.
- HTTP service methods for course and student data.

### Getting started

Use Flutter with Dart `^3.6.1` or a compatible version.

```bash
flutter pub get
flutter run
```

Review `lib/services/api_service.dart` and configure an available backend before testing the API-backed screens. The backend is not included in this repository; some screens may use example data. This repository does not establish official university affiliation or production availability.

### Code structure

- `lib/screens/` — campus information screens.
- `lib/services/` — HTTP requests and URL launching.
- `lib/widgets/` — shared app bar and transcript calculator.
- `lib/main.dart` — application entry point.

</details>
