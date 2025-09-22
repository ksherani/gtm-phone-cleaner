# gtm-phone-cleaner
This JavaScript snippet removes brackets (), dashes -, slashes /, spaces, +1 or leading 1  from phone numbers before tracking them in Google Analytics 4 (GA4).

GTM Phone Cleaner – Clean Phone Numbers for GA4

This repository contains a Google Tag Manager (GTM) JavaScript variable that removes unnecessary characters from phone numbers before sending them to Google Analytics 4 (GA4).

📌 Why Use This?

When tracking phone clicks or form submissions, phone numbers often contain characters like:
	•	( ) brackets
	•	- dashes
	•	/ slashes
	•	+1 or 1 (US country codes)
	•	spaces

These can cause duplicate phone numbers in GA4 reports. This script standardizes them into a clean numeric format.

⸻

🚀 Setup Guide
	1.	Open Google Tag Manager.
	2.	Go to Variables → New → User-Defined Variable → Custom JavaScript.
	3.	Paste the code above.
	4.	Replace {{Click Text}} with your variable (e.g., Click Text, Form Field, or another phone input variable).
	5.	Save and publish your container.
	6.	In your GA4 tag, use this variable to send the clean phone number as an event parameter.

⸻

📊 Example in GA4

If a user clicks +1 (555) 123-4567,
this script sends 5551234567 to GA4 instead.

⸻

📹 Tutorial

Watch the full tutorial on YouTube:
👉 https://youtu.be/JOIFpc71g4U

⸻

🏷️ Tags

GA4 Google Tag Manager Phone Tracking JavaScript Analytics
