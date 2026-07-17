# AttendIQ
Degree FYP


1. PROJECT OVERVIEW
-------------------
AttendIQ is a secure, intelligent attendance-taking application designed 
for academic institutions. Unlike traditional systems, AttendIQ employs 
Behavioral Biometrics (Identity-as-a-Service) to ensure the person 
marking attendance is the actual student, preventing proxy attendance.

2. CORE FEATURES
----------------
- Multi-Modal Behavioral Authentication:
    * Gait Analysis: Verifies identity based on walking patterns using 
      accelerometer sensors.
    * Touch Dynamics: Analyzes interaction patterns such as screen 
      pressure and touch frequency.
    * Keystroke Dynamics: Monitors typing rhythm (Flight Time/Dwell Time) 
      during data entry.
- Machine Learning Integration:
    * Powered by Google ML Kit Barcode Scanning for fast and accurate 
      QR code recognition.
- Secure Student Management:
    * Student ID-linked registration.
    * Full Name and Profile Initial generation.
- Dashboard & Quick Links:
    * Integrated web viewer for school portals and libraries.
    * Customizable dashboard links for quick access to academic resources.

3. TECH STACK
-------------
- Language: Kotlin (Modern Android Development)
- Architecture: XML-based Views with Material Design 3
- Libraries:
    * CameraX: High-performance camera integration.
    * Google ML Kit: Barcode/QR Code scanning engine.
    * Biometric Support: Integration for Fingerprint/Face ID.
    * Sensors: Android SensorManager for Gait detection.

4. INSTALLATION & SETUP
-----------------------
1. Open the project in Android Studio (Jellyfish or newer).
2. Ensure you have the Android SDK 35 (API 35) installed.
3. Sync the project with Gradle files.
4. Run the app on a physical Android device (Sensors and Camera are 
   required for full functionality).

5. USER GUIDE
-------------
- Registration: Enter your Student ID, Full Name, and credentials. The app 
  will store your behavioral baseline.
- Marking Attendance: 
    1. Tap "Scan QR" on the dashboard.
    2. The system will perform a background "Identity Check."
    3. You must walk naturally or interact with the screen to satisfy 
       behavioral verification.
    4. Upon successful verification, scan the classroom QR code.
- Sidebar: Use the sidebar to access the Overview or Sign Out. Your 
  profile name and initials are displayed at the bottom footer.

6. SECURITY NOTE
----------------
This application is designed as a research-oriented security tool. It 
leverages unique behavioral patterns to mitigate the risk of identity 
theft in attendance recording.


