# EventLogger
 Single page HTML file for managing employee data, creating schedules, and logging events to be communicated between shifts.

Uses LocalStorage instead of a database, so each device using it will have unique data storage.

Logs can be exported as XML to be shared and imported with other users, as well as import invents between shifts.
-IMPORTANT- clearning browser cache will clear any stored employee and event data. 

Recommended usage: using the app is as simple as opening the EventLogger.html in a web browser.

1. If you are setting this up for a new location, click the Change Location button to submit a new location.
2. Have all employees who will be using this app enter their information in the Employee Manager. Each employee can choose a color that will be the background color of events that they log. Optionally, you can also enter their shift and schedule to generate a schedule with the button at the bottom of the Employee Manager.
3. Employees can now select their name from the Employee dropdown in the Event Logger page, create a timestamp, enter the information about the event they are logging, and submit it.
4. At end of shift, the shift lead can export the shift's events as an XML file to archive the events, then import that file to load those events into the Imported Events table for the next shift to look over.
5. Once all shifts are complete, the manager can click the Print Report button to generate a printer friendly view of the event tables. You can choose "Save as PDF" in the print preview settings to save a PDF of the event logs.
6.  If there is too much whitespace between the tables in the print preview, exit the print preview and click the "Disable Page Break" checkbox, then print again.
