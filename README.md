# Google Calendar Manager for Event Series with Multiple Partners
The Google Calendar Manager is a Crowd-Sourcing Application that allows you to cultivate events from multiple different people or to manage your own events for an event series. Information for a individual event is entered through a Google Form that has a connection through the Google API to a Google Sheet. With this application, you can use this Google Sheet in order to manage a Google Calendar using the functionality of the spreadsheet. The code in the file above contains the script for the Google Sheet, allowing it to act as the middle point between the crowd-sourcing in the Google Form and uploading the info into a Google Calendar.

The Functionality and Set-Up of the Google Sheet can be found below.

# Functionality
Through this application, you can easily create and verify events. All information that is inputted into the Google Form will automatically fill up the Google Sheet. The Google Sheet contains a **Verification** column and a **Mark as Incomplete** column each with check boxes. Functionality is listed below:

- When you check off boxes in the **Verification** section, the given event will be added to the calendar. Events that have the check removed will be taken off of the calendar when the script is run.
- When you check off boxes in the **Mark as Incomplete** section, it makes the given event on the calendar private, meaning only people with edit access of the calendar can see it. Private events are marked as red while Public events are marked as green.

The script runs automatically every hour. In the case of technical difficulties or you wish to update the Google Calendar instantly, Go into **Extensions then go into the App Script.** Then click run. This will make the google calendar update. If you also wish to see the log of what has been added or removed, you can go to the **Executions** section on the side-bar of the App Script section. There, you can see the log of what has been added and deleted from the calendar.

If you have any questions or concerns, please don't hesitate to email **garcia.andre@northeastern.edu** with the subject **Google Calendar Manager Help**

# Set Up
Get started by copying the following Google Sheet: https://docs.google.com/spreadsheets/d/1zCqHDdnZ2B0cgRPnOD1ce7djkkZdMZ1__bMW8m6_mWg/edit?usp=sharing

This will also create a copy of the Google Form, you can access it by clicking **Tools then Manage Form.**

Then, you have to insert the **Google Calendar ID** into the top line of the code. Go into **Extensions then go into the App Script.** There, you should be able to see the Back-End. Insert the ID into the first line in-between the **" "**. After this, preparation is complete.
Instructions on how to obtain the Google Calendar can be found here: https://docs.simplecalendar.io/find-google-calendar-id/


