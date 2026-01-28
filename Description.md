# EduShedule
Project Description: EduSchedule
# 🎯 Purpose
EduSchedule is a high-performance Android application designed to centralize and simplify the academic experience. Instead of forcing students to juggle multiple calendars and syllabus documents, EduSchedule provides an intelligent, time-aware dashboard that prioritizes what matters most at any given second.

# 📱 Functional Modules
# 1. The Dynamic Dashboard (DashboardScreen.kt)
The dashboard acts as the application's "Command Center," featuring four primary components:

Active Class Monitor: A real-time tracker for the current lecture. It calculates the elapsed time and displays a visual progress bar with the exact percentage of minutes remaining.

Daily Deadline Triage: A focused display of "Upcoming Class" cards specifically filtered for assignments and deadlines due within the current 24-hour cycle.

Assessment & Exam Portal: A dedicated section for high-stakes events, pulling data from Assessment.kt to ensure students are prepared for upcoming tests.

Institutional Roadmap: A specialized feed for school-wide events, including holidays, registration deadlines, and graduation ceremonies.

# 2. Intelligent Timetable (TimetableScreen.kt)
A structured, digital version of the traditional weekly schedule:

Monday–Friday Layout: Organized view of the academic week.

Attendance Tracking: Clearly defines expected attendance for each day.

Conflict Prevention: Integrated logic (via ConflictChecker.kt) ensures that overlapping classes or exams are flagged immediately.

# 3. Smart Notifications & Wellness
Beyond scheduling, the app focuses on the student's well-being and punctuality:

Contextual Reminders: Automated alerts for class starts and submission deadlines.

Health Integration: A built-in water intake reminder (WaterReminderReceiver.kt) to encourage healthy habits during long study sessions.

# 🏗 Technical Highlights
Language: Kotlin

UI Framework: Jetpack Compose (Declarative UI)

Database: Room Persistence Library (Offline-first architecture)

Architecture: MVVM (Model-View-ViewModel) for clean separation of concerns.
