# Course Schedule Planner V1

Android project for Dr.Ashraf El-Maghraby.

## Implemented in V1
- Saturday–Friday weekly schedule with date shown under every day.
- Saturday–Thursday: 2:00 PM–10:00 PM; Friday: 10:00 AM–10:00 PM.
- 16 regular weeks + Final Exam Week 1, 2, 3.
- Today's Schedule panel with one-occurrence cancel (X).
- Green available / red booked / gray unavailable visual language.
- Booking conflict prevention, including partial overlap.
- 90-minute or 120-minute course duration using preset time lists.
- Repeat Schedule, Copy Week, edit one occurrence or matching repeated series.
- Course single-select list, logical categories, Add New Course.
- Multiple groups per course.
- Add Student with WhatsApp/mobile number.
- Student transfer between groups.
- Group student count and Group Capacity (including Near Full / Full state).
- Quick Search by student, WhatsApp, course or group.
- Limited Payments tab: student payment + selected-day total only.
- Light/Dark mode. In Dark Mode, selected day name is yellow on blue.
- Dr.Ashraf El-Maghraby + current day/date/month in the header.
- Backup / Restore to JSON using Android Storage Access Framework.
- Local persistence on the device through SharedPreferences.

## Build
Open the project folder in Android Studio, allow Gradle/SDK sync, then use:
Build > Build APK(s)

Project configuration:
- applicationId: com.ashraf.courseschedule
- minSdk: 23
- targetSdk / compileSdk: 35
- Android Gradle Plugin: 8.7.3
- Java: 17

The UI is a local offline WebView packaged inside the APK. No internet permission is requested.
