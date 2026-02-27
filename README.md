Overview
FocusFlow is a privacy-first, offline Django web application designed to help students manage academic stress and workload intelligently. 
The system uses self-trained machine learning models to analyze user inputs such as sleep hours, study time, screen time, mood, and task deadlines to predict stress levels and productivity scores. 
Based on these predictions, FocusFlow prioritizes tasks and provides smart in-app reminders — all without using any external APIs or internet connectivity.

Problem Statement
Students frequently struggle with academic overload, missed deadlines, and unmanaged stress. 
Most productivity applications depend on cloud services and APIs, which compromise privacy and require continuous internet access. 
There is a need for an intelligent, offline, privacy-focused solution that not only tracks tasks but also predicts stress and optimizes workload.

Solution
FocusFlow provides an AI-driven, fully offline system that:
Allows users to add, update, and track tasks with deadlines and difficulty levels
Collects daily habit data such as sleep, study hours, screen time, and mood
Predicts stress level (Low / Medium / High) using machine learning
Calculates productivity score based on workload patterns
Automatically prioritizes tasks based on urgency and stress impact
Sends in-app reminders for upcoming and overdue tasks
Displays stress and productivity trends through a dashboard
All computations and data storage occur locally to ensure maximum privacy.

Key Features
Offline AI-Based Stress Prediction
Smart Task Prioritization System
Productivity Score Estimation
Due-Work Reminder & Alert System
Responsive Design (Mobile + Desktop Compatible)
No APIs Used (Fully Open-Source & Local Processing)

Tech Stack
Backend: Django
Machine Learning: Scikit-learn
Database: SQLite
Frontend: HTML, CSS, JavaScript
Deployment: Localhost Server (Offline Usage)
