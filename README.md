**CARDINAL RULES TO MAKE IT EASIER TO WORK TOGETHER:**
Communication is the main factor that falls during projects. With this in mind - in this file please:
1. Put each new **proposal** at the top with a date like: **"PROPOSED:2025.11.09: PROPOSAL: xxxxxxxxxx"**
2. Put each new **implemented** change (branch that isn't commited yet) with a date like this: **"2025.11.10: BRANCH: xxxxxxxxxx"** over the proposal.
3. Put each new **committed** change with a date like this: **"2025.11.11: COMMITTED: xxxxxxxxxx"** over the proposal / implemented

For example (complete flow for a simple feature):
**2025.11.11: COMMITTED: xxxxxxxxxx**
Committed to both merged to main
**2025.11.10: BRANCH: Google login + email**
Implemented. Added also email+pass to it. Branch #2. Pull Request created.
**2025.11.09: PROPOSAL: Google login**
Put Google login through Firebase.

**AGREE?**


**==============================**


**2025.11.11 (Polish Independence Day): PROPOSAL: Structure for Scalability**
Superuser can create an organisation and any admins, users and any fields for this organisation.
Superuser can delete an organisation and any admins, users and any fields for this organisation.
Admins can create any users and any fields visible to all admins and users.
Within the same organisation - all admins and users share the same data by default but admin can hide any data from the user.
The default fields for any newsly created organisation with its admins and users are: # and Issue Subject.
[VISUAL WITH PANELS PER LEVEL WILL BE INSERTED HERE]
Create an admin account that will approve next users.


**2025.11.11 (Polish Independence Day): PROPOSAL: Basic Login**
Create a web app that will allow the user to sign up using either: GoogleAuthorisation or email+pass. When the user logins - if it's with google: his email will display in blue. If with email+pass - in red. 
Make sure that the user with the same email can sign in using both methods.
All the users who signed up / logged in will be stored in a firebase, including every time they signed up / logged in. 
After logging in - there will be "Recent Activity" field at the bottom of the page that will show times & dates of the last 5 sign inns.
The app will be deployed on vercel. Secret keys shall be stored in vercel env variables. 
Add a text field that when user enters (without pressing enter) - will be saved to his profile and visible on the next login.
Add a dropdown "Interested?" with Yes and No that will be saved and visible on the user next login. 
Push it directly to the Github repo.

Create a dash board master user that will send invites to each admin under separate domains / organisation. 
Structure of the database: 
Superuser dashboard to onboard be organisation => Organisation => users including admins and normal users => activity + data


**2025.11.11 (Polish Independence Day): PROPOSAL: Functionality to raise the issues for communication within the team**
<img width="1160" height="653" alt="image" src="https://github.com/user-attachments/assets/74f9f672-1e32-4bb8-9f1b-a437b1bc8c50" />
<img width="1162" height="653" alt="image" src="https://github.com/user-attachments/assets/26815c99-490c-473a-aecc-0f7c5106913f" />
<img width="1161" height="657" alt="image" src="https://github.com/user-attachments/assets/acaecd36-7808-42cb-a41a-fcc4a4f3cdad" />
<img width="1162" height="662" alt="image" src="https://github.com/user-attachments/assets/b00b637d-eacf-48c8-8b93-ecae8eaddca3" />
<img width="1162" height="657" alt="image" src="https://github.com/user-attachments/assets/377d4219-ba80-4c8c-9179-4b03ad596cc3" />
