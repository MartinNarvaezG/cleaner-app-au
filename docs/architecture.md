This document describes the high-level architecture of the CleaningPro MVP.

---

## 1. App Type
The MVP will be a **local Python application** with simple UI (later Kivy).

All data is stored **locally** using JSON files.

---

## 2. Main Modules

### ✔ Clients Module
Handles:
- Creating clients
- Editing clients
- Listing clients
- Storing client details

### ✔ Jobs Module
Handles:
- Creating a job
- Linking a job to a client
- Storing job duration, checklist, photos, notes

### ✔ Checklist Module
Handles:
- Default checklist structure
- Marking items as done
- Saving checklist status

### ✔ Timer Module
Handles:
- Job time start / stop
- Duration calculation

### ✔ History Module
Handles:
- Listing previous jobs
- Showing job details

---

## 3. Data Storage

We use JSON files stored in `/data/` folder:

- `clients.json`
- `jobs.json`
- `checklist.json`

Photos will be stored in:
- `/photos/jobID_before.jpg`
- `/photos/jobID_after.jpg`

---

## 4. Application Flow (High Level)

1. User selects a client  
2. User starts a new job  
3. User goes through checklist  
4. User tracks time  
5. User takes photos  
6. Job is saved into history  
7. User can review job details later  
