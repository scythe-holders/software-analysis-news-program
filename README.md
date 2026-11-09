# software-analysis-news-program
software analysis project
1. Project description:
a platform that connects content creators with media reviewers. Creators can submit their media content, and reviewers can evaluate it.
2. Problem statement:
Content creators need a simple way to submit their work and track its review status. Reviewers need an organized system to manage incoming submissions.
3. MVP goal:
The goal of Homarasa's MVP is to allow content creators to submit their work, receive a review decision, and track their submission status.
For the semester MVP, I recommend submitting an existing media URL first, leaving direct video file uploads for a later iteration.
US-01	Register, log in, and log out securely	
US-02	Submit a media work	
US-03	View my previous submissions	
US-04	View pending work as a reviewer	
US-05	Approve or reject a submission	
US-06	View the decision and rejection reason	
US-07	Prevent unauthorized access to submissions	
US-08	Upload actual media files	
US-09	Request revisions and resubmit work	
US-10	Search and filter submissions	
US-11	Receive status notifications	
US-12	View administrative statistics	
US-13	Automatically suggest content categories	

Story	Acceptance criteria
US-01	Valid credentials allow login; invalid credentials are rejected; logout ends access; users cannot register themselves as reviewers.
US-02	A valid submission is saved with a unique ID and Pending status; invalid fields produce errors without creating a record.
US-03	Submissions remain visible after refresh and later login; users cannot view another creator's submissions.
US-04	Reviewers can see pending submissions; creators cannot access the reviewer queue.
US-05	Reviewers can approve or reject; rejection requires a reason; repeated decisions cannot overwrite the original.
US-06	Creators see the correct status and rejection reason; decisions remain available after returning later.
US-07	Anonymous requests, unauthorized users, and creators attempting reviewer actions are rejected by the backend.


