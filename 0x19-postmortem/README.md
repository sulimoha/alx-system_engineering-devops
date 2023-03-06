
# Issue Summary
- Between the hours of 12:00 and 13:45 on February 13, 2023, EDT, all the five call center agents encountered down phone calls period.
- The agents received zero calls during that period but their calling app shows missed calls.
- The calling app admin accidentally applied Saturday business hours on weekdays business hours.

# Timeline
-	13:00 EDT the agents noticed zero phone calls came in which has never happened for this long period of time. Also, their calling app showing missed calls for calls that never received
-	13:05 EDT the IT guy was notified.
-	13:10 IT started checking if their calling app was set to silent. Wasn’t the case.
-	13:12 IT checked the internet connection, speed, etc. Nothing was abnormal.
-	13:15 IT asked the agents to sign out and sign in back to their calling app. Did not solve the issue.
-	13:20 IT tried to call the mainline with his phone and received a voicemail greeting asking to leave a message because it is after business hours (which is not true)
-	13:30 The IT escalated the issue to the calling app admin and got him involved.
-	13:45 the issue was resolved.

# Root cause
-	It is found out that the app calling admin had set the working hours for Saturday from 7:00 to 12:00 EDT. He accidentally applied Saturday business hours on weekdays. That is why on Monday at 12:00 EDT the voicemail greeting was activated and the agents were not receiving calls.
-	The issue was fixed by correcting the business hours for weekdays.

# Corrective and preventative measures
-	Anytime any modification takes place on the calling app settings, a test must be conducted on different times of the day to make sure the calling app is working properly
-	Anytime any modification take place, the action must be shared with IT and call center agents to keep them posted






