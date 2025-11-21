This document defines the JSON structure for the MVP.

---

## 1. Client Object

```json
{
  "id": "client_001",
  "name": "John Smith",
  "address": "123 Example St",
  "phone": "0411111111",
  "notes": "Dog inside the house",
  "created_at": "2025-01-01"
}
```

## 2. Job Object

```json
{
  "id": "job_001",
  "client_id": "client_001",
  "date": "2025-01-04",
  "duration_minutes": 95,
  "checklist": {
    "kitchen": {
      "sink": true,
      "floors": false,
      "bins": true
    }
  },
  "photos": {
    "before": "photos/job_001_before.jpg",
    "after": "photos/job_001_after.jpg"
  },
  "notes": "Kitchen required extra time"
  "status": "completed" 
}
```

## 3. Checklist Template

```json
{
  "kitchen": ["sink", "floors", "counters", "bins"],
  "bathroom": ["toilet", "shower", "mirror", "floors"],
  "living_room": ["vacuum", "dusting", "windows"]
}
```

