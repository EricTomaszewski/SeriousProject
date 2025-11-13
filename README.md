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


Firebase environment for backend (database + signin/signup ease) 
Vercel environment for frontend.
Main language - TBC but it needs to be good for web apps.


**==============================**


**2025.11.11 (Polish Independence Day): PROPOSAL: Structure for Scalability [THE SCALABILITY]**
Superuser can create an organisation and any admins, users and any fields for this organisation.
Superuser can delete an organisation and any admins, users and any fields for this organisation.
Admins can create any users and any fields visible to all admins and users within a given organisation.
Within the same organisation - all admins and users share the same data by default but admin from a given organisation can hide any data from the user in a given organisation.
The default fields for any newsy created organisation with its admins and users are: # and Issue Subject. Any others are Adming for a given organisation dependant.
Create an admin account that will approve the next users.
Admin & User will get an email to activate the account that then will be used for login.
<img width="1183" height="257" alt="image" src="https://github.com/user-attachments/assets/39297dab-f5e9-4646-b427-de19dc0961b9" />



**2025.11.11 (Polish Independence Day): PROPOSAL: Functionality to raise the issues for communication within the team [THE VALUE]**
Add new issue:
<img width="1160" height="653" alt="image" src="https://github.com/user-attachments/assets/74f9f672-1e32-4bb8-9f1b-a437b1bc8c50" />

Dashboard overview:
<img width="1162" height="653" alt="image" src="https://github.com/user-attachments/assets/26815c99-490c-473a-aecc-0f7c5106913f" />

Visible columns:
<img width="1161" height="657" alt="image" src="https://github.com/user-attachments/assets/acaecd36-7808-42cb-a41a-fcc4a4f3cdad" />

Default values when adding an issue:
<img width="1162" height="662" alt="image" src="https://github.com/user-attachments/assets/b00b637d-eacf-48c8-8b93-ecae8eaddca3" />

Filters after adding issues:
<img width="1162" height="657" alt="image" src="https://github.com/user-attachments/assets/377d4219-ba80-4c8c-9179-4b03ad596cc3" />
