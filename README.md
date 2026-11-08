# phys

**Beyond the Clinic.**

phys is an AI-powered physiotherapy app designed to make rehabilitation easier for patients and more efficient for physiotherapists.

It connects clinics and patients, providing personalized exercise plans, real-time movement feedback and progress tracking, all from a smartphone.

## The Problem

Physiotherapy doesn't end when patients leave the clinic.

At home, patients often forget instructions, struggle to perform exercises correctly or lose motivation. Meanwhile, physiotherapists have little insight into how their patients are progressing between appointments.

## Our Solution

phys helps patients follow their rehabilitation plans at home while allowing physiotherapists to monitor their progress.

The app includes:

- **AI Treatment Planning:** Turns medical reports into personalized exercise plans, reviewed and approved by physiotherapists.
- **Movement Tracking:** Uses the phone's camera to measure joint angles, count repetitions and detect incorrect movements.
- **Real-Time Feedback:** Provides visual and voice instructions during exercises.
- **Progress Tracking:** Records exercise performance, mobility and pain levels over time.
- **Therapist Dashboard:** Allows physiotherapists to manage treatment plans and follow patient progress.
- **HomeAdapt:** Suggests exercise modifications based on available space and equipment.

## Why phys?

Most digital rehabilitation tools focus on tracking prescribed exercises.

We also focus on simplifying the physiotherapist's workflow, from creating personalized treatment plans based on medical reports to monitoring patients at home.

Our goal isn't to replace physiotherapists, but to give them better tools to support their patients beyond the clinic.

## Technologies

- Android (Java)
- HTML, CSS, JavaScript
- Android WebView
- MediaPipe Pose
- Computer Vision
- Claude AI
- OCR

## Running the App

The Android project is located in `fizio-android/`.

To build the APK, run the following command from that directory:

```powershell
.\build-apk.ps1
```

The application requires the necessary Android SDK and JDK setup. Some features also require a configured backend and API access.

## What's Next?

We plan to integrate smartphone health data and depth-sensing technology to improve movement analysis and make rehabilitation tracking more accurate.

## Team

Developed by **Team T.A.D.A.** for **Garaža Hackathon 2026**.

*phys is a hackathon prototype. AI-generated treatment suggestions require physiotherapist approval.*

**phys | Beyond the Clinic.**
