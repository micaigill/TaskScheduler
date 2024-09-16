# **Task Scheduler App with AI Optimization**

A web application that allows users to create, manage, and optimize their schedules using Google Calendar and AI-powered event scheduling. Built with **React** and **TypeScript** for the frontend, **Firebase** for backend services (including authentication and real-time data handling), and the **OpenAI GPT API** for intelligent scheduling. The app integrates with the **Google Calendar API** for calendar syncing and scheduling optimization.

## **Features**
- **Google Calendar Integration**: Sync with your Google Calendar and view/manage your tasks and events in real time.
- **AI-Powered Task Scheduling**: Automatically optimize your schedule by finding the best time slots for new tasks using the GPT API.
- **Custom Scheduling Constraints**: Define scheduling windows (e.g., current day to two weeks) and specify days to avoid (e.g., weekends) for better control over how your tasks are scheduled.
- **To-Do List Integration**: Input your to-do list with task names, durations, and priority levels. The app will optimize the scheduling of these tasks based on your existing calendar.
- **Priority Task Management**: Assign priority levels (1-3) to your tasks to ensure that higher-priority tasks are scheduled before lower-priority ones.
- **Ignore Specific Days**: Specify certain days (e.g., weekends or holidays) to exclude from scheduling new tasks, while retaining any existing events on those days.

## **Tech Stack**
- **Frontend**: 
  - [React](https://reactjs.org/) (with [TypeScript](https://www.typescriptlang.org/))
- **Backend**: 
  - [Firebase](https://firebase.google.com/) (Firestore, Authentication, Cloud Functions)
- **APIs**:
  - [OpenAI GPT API](https://beta.openai.com/docs/) for AI-driven scheduling optimization.
  - [Google Calendar API](https://developers.google.com/calendar) for syncing tasks and calendar events.

## **Project Setup**

### **1. Clone the Repository**
```bash
git clone https://github.com/micaigill/TaskScheduler.git
cd TaskScheduler
```
