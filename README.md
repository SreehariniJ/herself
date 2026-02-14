HERSELF 
Basic Details

Team Name: HERSELF

Team Members

Member 1: Sreeharini J 
Member 2: Sreya S

Hosted Project Link

https://github.com/SreehariniJ/herself

Project Description

HERSELF is an AI-powered women’s safety and empowerment mobile application. It integrates emergency protection features, emotional AI companionship, behavior-based suggestions, and daily wellness tracking into one unified platform.

The Problem Statement

Women often rely on multiple apps for safety alerts, mental wellness, productivity, and health tracking. This fragmentation increases stress and reduces reliability during emergencies. There is a need for one intelligent, privacy-focused companion that supports safety, emotional well-being, and daily life management.

The Solution

HERSELF combines an SOS safety system, AI-powered digital companion, energy-based productivity suggestions, and wellness tracking into a single Flutter-based application. It also includes behavior learning that adapts suggestions based on user mood and energy trends.

Technical Details
Technologies/Components Used
For Software:

Languages used: Dart
Frameworks used: Flutter
Libraries used: Provider, sqflite, Google Generative AI (Gemini), Speech-to-Text, Text-to-Speech
Tools used: VS Code, Git, GitHub, Android Studio

Features

Feature 1: SOS Emergency Alert – Sends WhatsApp alert with live location to emergency contacts.

Feature 2: Travel Mode – Smart check-in system that auto-triggers SOS if user does not confirm safety.

Feature 3: HerTalk AI Companion – Empathetic AI chatbot with voice interaction.

Feature 4: Boost Mode – Mood and energy-based activity recommendations.

Feature 5: Behavior Learning System – Learns user trends locally for personalized suggestions.

Feature 6: Daily Essentials – Task planner, hydration tracker, sleep tracking.

Implementation
For Software:
Installation
git clone https://github.com/SreehariniJ/herself.git
cd herself
flutter pub get

Run
flutter run -d android
or
flutter run -d windows
or
flutter run -d chrome

Project Documentation

Screenshots

Login
<img width="497" height="799" alt="Screenshot 2026-02-14 092737" src="https://github.com/user-attachments/assets/67cd08fd-af2c-4697-8bbd-66f449774039" />

Signup
<img width="495" height="799" alt="Screenshot 2026-02-14 092804" src="https://github.com/user-attachments/assets/9f069038-e984-436d-8b7a-2c9615764ff3" />

Home page
<img width="490" height="742" alt="Screenshot 2026-02-14 092917" src="https://github.com/user-attachments/assets/cfed634e-7f72-42f9-b379-3ac3f2d581c1" />
<img width="487" height="794" alt="Screenshot 2026-02-14 092936" src="https://github.com/user-attachments/assets/8153561f-3e69-47e1-881a-53a7a9979ac1" />

Modules

Boost
<img width="496" height="790" alt="Screenshot 2026-02-14 092957" src="https://github.com/user-attachments/assets/d7e5cda2-98ae-4204-8924-2d0032e99c89" />

HerTalk
<img width="491" height="802" alt="Screenshot 2026-02-14 093020" src="https://github.com/user-attachments/assets/702fdb16-d880-41b5-94d1-b2e8550cd79a" />

Daily Planner
<img width="490" height="786" alt="Screenshot 2026-02-14 093034" src="https://github.com/user-attachments/assets/f7c1bb2c-e301-4205-b6e2-3dfbb7debe52" />

Health Care
![WhatsApp Image 2026-02-14 at 9 36 05 AM](https://github.com/user-attachments/assets/ca675a7f-7940-4720-84c7-8eee2524a5a9)
![WhatsApp Image 2026-02-14 at 9 36 05 AM](https://github.com/user-attachments/assets/57a7d18e-a991-497d-9fb3-58c3ab8f62c3)

Guardian
![WhatsApp Image 2026-02-14 at 9 35 28 AM](https://github.com/user-attachments/assets/8786d8d3-44f4-4503-a3dd-285af7ad543d)

Workout
![WhatsApp Image 2026-02-14 at 9 35 15 AM](https://github.com/user-attachments/assets/6383c1f4-409d-4c2b-804d-685091cda9c9)


Diagrams

System Architecture:
![WhatsApp Image 2026-02-13 at 8 04 00 PM (1)](https://github.com/user-attachments/assets/14d4fec6-12ba-4b07-a35f-b3a0a01d6451)

Architecture Diagram
The system consists of:

Flutter Frontend

Local SQLite Database

Gemini AI API Integration

Location & Notification Services

WhatsApp Intent Integration

Data Flow:
User Input → Behavior Engine → AI/Module Recommendation → Output Display → Local Storage Update

Application Workflow:

Workflow
User Login → Home Dashboard → Select Module (Guardian / Boost / HerTalk / Planner) → Module Execution → Data Stored Locally → Behavior Learning Engine Updates Trends

For Mobile Apps:
App Flow Diagram

User Registration/Login
↓
Dashboard
↓
Choose Module
↓
Perform Action (SOS / Chat / Boost Suggestion / Add Task)
↓
Store & Analyze Behavior
↓
Personalized Suggestion

Installation Guide
For Android (APK):

Download APK from Release Link

Enable "Install from Unknown Sources"

Open APK file

Install and launch

Building from Source
flutter build apk


For iOS:

flutter build ios


AI Tools Used (Optional - Transparency)

Tool Used: ChatGPT
Purpose: Architecture structuring, debugging, documentation refinement
Key Prompts Used:

"Design AI companion architecture"

"Generate Flutter state management structure"

"Debug Gemini API integration"

"Improve project README structure"

Percentage of AI-generated code: ~20% (Boilerplate & debugging assistance)

Human Contributions:

Full system architecture design

Core module implementation

UI design decisions

Behavior learning logic

Testing and integration

Complete frontend development

AI integration

Safety module implementation

Database design

Documentation

Testing & optimization

License

This project is licensed under the MIT License.

Made with ❤️ for Women’s Safety & Empowerment
