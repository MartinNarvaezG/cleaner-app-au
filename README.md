# cleaner-app-au
App to organize cleaning jobs: manage clients, checklists, time tracking, photos, and service history

# Cleaner App Australia 🧽🇦🇺

App to bring order, efficiency, and clarity to daily cleaning work in Australia.

Instead of improvising with paper notes, WhatsApp messages, or memory, this app gives cleaners a simple tool to manage checklists, time spent on each job, photos as proof of work.

---

## 🧩 Problem

Many cleaners and small cleaning teams in Australia still manage their work using:

- Lack of visual evidence
- Missing or unclear job instructions
- No structured system for job tracking 
- Difficulty maintaining professionalism at a small scale 

This leads to misunderstandings, lost jobs, and less professional service.

---

## 💡 Solution

A simple, intuitive app focused on cleaners that:

- Replaces improvisation with **structured checklists**  
- Tracks **time spent** on each job  
- Allows cleaners to **take and store photos** as proof of work  
- Works well for both **solo cleaners** and **small cleaning businesses**

---

## 🎯 Target Users

- **Solo cleaners** working for agencies or directly with clients  
- **Small cleaning teams** (2–10 people) who need more organization  
- **Supervisors / owners** who want visibility of jobs and quality  
- **Clients** (indirectly) who receive better reports and invoices

---

## 🚀 MVP Scope (First Version)

The MVP will focus on:

1. **Client Management**
   - Create new clients
   - Edit existing clients
   - Delete clients
   - Store basic information:
     Name
     Address
     Phone number
     Notes or cleaning preferences
   - Display a list of all clients
     
2. **Cleaning Checklists**
   - Pre-defined checklists for common areas (kitchen, bathroom, living room)
   - Mark tasks as done / not done

3. **Photos as Proof**
   - Attach photos to a job (before/after or final result)

4. **Time Tracking**
   - Start/stop timer for each job  
   - Store total time spent

5. **Job Creation & Management**
   - Create a new cleaning job
   - Assign the job to an existing client
   - Add optional notes
   - Select date of the job
   - Save job information locally

6. **Job History**
   - List all completed jobs
   - Filter or view jobs by client
   - Show details of each job:
     Checklist completed
     Total times
     Notes
     Before/after photos 

 7. Local Data Storage
    - All data stored on the device
    - Format: JSON for simplicity (SQLite optional)
    - No login required
    - No internet required
    - Auto-save changes 

---

## 🛠️ Tech Stack (Planned)

> This is still a work in progress and may change.

- **Frontend:** (TBD – e.g. React, React Native, Flutter, etc.)
- **Backend:** (TBD – e.g. Node.js, Django, FastAPI…)
- **Database:** (TBD – e.g. MySQL, PostgreSQL, Firebase, etc.)
- **Platform:** Initially web or mobile web, later possibly native app.

---

## 📁 Repository Structure

```text
docs/           → Product and planning documentation
frontend/       → Frontend app (once started)
backend/        → Backend API and services (once started)
notes/          → Personal research notes, market insights, ideas
