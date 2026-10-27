# TrackApplying

TrackApplying is an Android app that helps university students keep track of
internship and job applications. It stores each application with its status
and deadline, sends a reminder a chosen number of days before the deadline,
and keeps a log of which CV version was sent to which company. All data is
stored on the device, so it works offline.

## Planned Features

**Must**
- Add, view, edit and delete applications (company, role, dates, status, notes)
- Deadline reminder notification, with the number of days set by the user
- CV version log: add, edit and delete entries and link one to an application

**Should**
- Search by company or role and filter by status
- Default reminder time in Settings
- Light and dark theme toggle
- Stats screen with a count per status

**Could**
- Sort applications by deadline
- Attach the real CV file to an application

## Tech Stack

- Language: Kotlin
- UI: Jetpack Compose (native Android)
- Local storage: Room (planned)
- Tools: Android Studio, Git and GitHub
- Minimum SDK: API 24 (Android 7.0)

## Project Status

planning and setup

## Setup Instructions

1. Clone the repo: `git clone https://github.com/byteofhoney/track-applying.git`
2. Open the folder in Android Studio.
3. Wait for Gradle sync to finish.
4. Select an emulator or connected phone and click Run.