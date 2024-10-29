# Google-Calendar-Manager
The Google Calendar Manager is a Crowd-Sourcing that allows you to cultivate events from multiple different people or to manage your own events. This is done through a google form that has a connection through the google API to a google sheet. You can use this google sheet to manage a google calendar using the functionality of the spreadsheet. The code in the file above contains the script for the google sheet, allowing it to act as the middle point between the crowd-sourcing in the google form and uploading the info into a google calendar.

The Functionality and Set-Up of the google sheet can be found below.

# Functionality
Through this application, you can easily create and verify events. All information that is inputted into the google form will automatically fill up the google sheet. 

- you can check off boxes in the **Verification** section. This will cause the event to appear on the google calendar. Events that have the check removed will be taken off of the calendar.
- You can also check off boxes in the **Mark as Incomplete** section. This makes events that are visible private, meaning only people with edit access of the calendar can see it. Private events are marked as red while Public events are marked as green.

The script runs automatically every hour. In the case of technical difficulties or you wish to update the google calendar instantly, Go into **Extensions then go into the App Script.** Then click run. This will make the google calendar update. If you also wish to see the log of what has been added or removed, you can go to the **Executions** section on the side-bar of the App Script section. There, you can see the log of what has been added and deleted from the calendar.

If you have any questions or concerns, please don't hesitate to email **garcia.andre@northeastern.edu** with the subject **Google Calendar Manager Help**

# Set Up
Get started by copying the following google sheet: https://docs.google.com/spreadsheets/d/1zCqHDdnZ2B0cgRPnOD1ce7djkkZdMZ1__bMW8m6_mWg/edit?usp=sharing

This will also create a copy of the google form, you can access it by clicking **Tools then Manage Form.**

Then, you have to insert the **Google Calendar ID** into the top line of the code. Go into **Extensions then go into the App Script.** There, you should be able to see the Back-End. Insert the ID into the first line in-between the **" "**. After this, preparation is complete.
Instructions on how to obtain the Google Calendar can be found here: https://docs.simplecalendar.io/find-google-calendar-id/


