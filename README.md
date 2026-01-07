**UniSync** is a mobile application wireframe designed to centralize key university operations for students, lecturers, and administrators.  
It connects users in a unified digital environment, offering streamlined access to timetables, announcements, assignments, attendance tracking, and campus networking — all in one platform.

## Key Features

### Secure Authentication
- Biometric login (fingerprint/face recognition)
- Password-based authentication
- Role-based access control

### QR Code Technology
- Instant QR code scanning for attendance
- Dynamic QR code generation for classes
- Offline scanning with automatic sync when online

### Real-time Analytics
- Live attendance tracking
- Comprehensive reporting system
- GPS location verification
- Geo-fencing capabilities

### offline Support
- Works without internet connection
- Automatic synchronization when online
- Local data storage and backup

### 🎨 Modern UI/UX
- Material Design principles
- Responsive mobile interface
- Dark/Light theme support
- Smooth animations and transitions

### Student Portal
- View **personal timetables** and upcoming classes.
- Receive **announcements** from lecturers and faculty.
- Track **assignments** with due dates and submission status.
- Monitor **attendance records** and progress analytics.
- Connect with peers and lecturers via a **discussion/networking hub**.

### Lecturer Portal
- Post and manage **announcements** for courses.
- Create and update **assignments** with deadlines.
- Record and monitor **student attendance**.
- Communicate with students through the **UniSync network hub**.
- View analytics and student participation summaries.

### Admin Portal
(Developed as a separate app — **UniSync Admin**)
- Dashboard with quick access buttons:
  - **User Management**
  - **Generate System Reports**
  - **View System Logs**
  - **Track User Locations (via GPS)**
- Add and manage student and lecturer accounts.
- Access **system-wide activity**, **attendance reports**, and **location analytics**.
- Customize application settings: themes, languages, and feature toggles.

---

Getting Started

### Prerequisites

- Android Studio Arctic Fox or later
- Android SDK 24 (Android 7.0) or higher
- Java 11 or later
- Internet connection for initial setup

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/lecturer-dashboard.git
   cd lecturer-dashboard
   ```

2. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an existing project"
   - Navigate to the project directory and select it

3. **Sync the project**
   - Android Studio will automatically sync Gradle files
   - Wait for the sync to complete

4. **Build and run**
   - Connect an Android device or start an emulator
   - Click the "Run" button or press `Shift + F10`

### First Launch

1. **Welcome Screen**: The app starts with an introduction to UniSync
2. **Role Selection**: Choose your role (Student, Lecturer, or Administrator)
3. **Registration**: Complete your profile with required information
4. **Authentication**: Set up biometric or password authentication
5. **Dashboard**: Access your personalized dashboard

### Build Configuration
The app uses Gradle with Kotlin DSL for build configuration:

- **Target SDK**: 36 (Android 14)
- **Min SDK**: 24 (Android 7.0)
- **Compile SDK**: 36
- **Java Version**: 11

### Dependencies
- **AndroidX Core**: Core Android libraries
- **Material Design**: UI components
- **WebView**: For hybrid app functionality
- **ConstraintLayout**: Advanced layout management

