# BreakWise 🧘‍♀️

**BreakWise** is a productivity and wellness app that helps users take mindful breaks.  
It supports **Pomodoro-style sessions**, **breathing reminders**, **affirmations**, and **stretch prompts**.

## 🚀 Tech Stack

- Java 21
- Spring Boot
- Maven
- Spring DevTools
- Spring Actuator

## ✅ MVP – Phase 1

### 1. Backend Setup
- Java 21
- Spring Boot Skeleton
- Health check endpoint (`/` returns "BreakWise backend is up")

### 2. Pomodoro Session Domain
- `Session` object (UUID, type, status, duration)
- Start session via `/sessions/start`
- Return session ID and expected end time

### 3. Notification (Mocked)
- REST endpoint simulates end-of-session alert

### 4. Affirmation Service
- `/affirmations/random` returns positive messages

## 🛠️ Developer Setup

1. Clone this repo
2. Open in IntelliJ (Java 21 SDK)
3. Run `BreakwiseBackendApplication.java`
4. Visit `http://localhost:8080/` to verify setup

## 🗂️ Project Management

Issues follow Jira-style formatting:
- **Title**
- **User Story**
- **Acceptance Criteria**
- **Priority**
- **Labels**

GitHub Projects used for Kanban tracking
