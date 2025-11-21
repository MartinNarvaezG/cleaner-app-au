**MVP SCOPE**

1. Client Management 

 - Create new clients
 - Edit existing clients
 - Delete clients
 - Store basic information: 
   Name 
   Address 
   Phone number 
   Notes or cleaning preferences 
   Display a list of all clients 

2. Cleaning Checklist 

 - Predefined cleaning checklists for common areas
 - Ability to mark items as completed
 - Ability to customize or edit the checklist for each job 

3. Job Creation & Management 

 - Create a new cleaning job
 - Assign the job to an existing client
 - Add optional notes
 - Select date of the job
 - Save job information locally 

4. Time Tracking 

 - Start timer
 - Pause/Resume timer (optional but recommended)
 - Stop timer
 - Save total duration of the job
 - Display total time in job history 

5. Before/After Photo Capture 

 - Use device camera to take photos
 - Save photos linked to the specific job
 - Display photos in the job detail view 

6. Job History 

 - List all completed jobs
 - Filter or view jobs by client
 - Show details of each job:
   Checklist completed
   Total time
   Notes
   Before/after photos 

7. Local Data Storage 

 - All data stored on the device
 - Format: JSON for simplicity (SQLite optional)
 - No login required
 - No internet required
 - Auto-save changes 

**Out of Scope (Not included in MVP)** 

These features will not be in the first version: 

 - Invoice generation
 - Payment tracking
 - Cloud sync
 - GPS route optimization
 - Multi-user/team features
 - App for clients
 - Automated reporting
 - Integrations with Stripe or PayPal 

 **Deliverables for MVP** 

 - Functional Android app (.apk)
 - Core UI screens
 - Fully functional client/job/checklist/timer/photo modules
 - Stable local storage
 - Basic error handling 
