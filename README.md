# İZÜ Campus App

A student-built Flutter application for campus information workflows. It includes screens for student records, courses, timetables, attendance, exam results and transcripts.

## Screens and components

- Student information and course details.
- Course and exam schedules, results and attendance views.
- Transcript view and a transcript calculation widget.
- Course materials, application forms and emergency contact information.
- HTTP service methods for course and student data.

## Getting started

Use Flutter with Dart `^3.6.1` or a compatible version.

```bash
flutter pub get
flutter run
```

Review `lib/services/api_service.dart` and configure an available backend before testing the API-backed screens. The backend is not included in this repository; some screens may use example data. This repository does not establish official university affiliation or production availability.

## Code structure

- `lib/screens/` — campus information screens.
- `lib/services/` — HTTP requests and URL launching.
- `lib/widgets/` — shared app bar and transcript calculator.
- `lib/main.dart` — application entry point.

## Türkçe

İZÜ kampüs bilgi sistemi için geliştirilmiş bir öğrenci projesidir. Ders programı, sınav sonuçları, devamsızlık ve transkript gibi ekranları Flutter ile sunar. Ders ve öğrenci verileri için HTTP servis katmanı içerir.
