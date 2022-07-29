## Description:

This project was given to us by Onecampus Academy. The project involved developing a PYTHON-ONLY application that can be used to convert Bootcamp times from **EST** to any of the **time zones requested**. The app should be able to convert the given date and time (Day and Time) to the requested time zone day and time.
The app should be able to store information about upcoming bootcamps by program type (Data Science, Machine Learning, and Data Analytics) and provide a corresponding list of schedules in any time zone or country requested by a student using ONLY Python containers.This app must not have any database implemented and should not read from or save to any file on disk. All data MUST be stored in Python code using containers ONLY.
#### Bonus:
The app can generate an alert for the student on their computer (no need for an email script) notifying the student 24 hours before their next bootcamp start time and 2 hours before bootcamp start time.
 
## Project Specifications:
#### App Capability
- The App should hold information about the times in countries around the world (two lists have been provided). One contains 588 countries' times while the other has times for 404 countries. should therefore be able to tell the current time in any country specified by the user by simply reading the current system time and time zone.
- The App should hold the time zones and times of the 200 time zones provided. should therefore be able to tell the time zone of any country specified by the user.
When provided the name of a source country and time zone, the app should be able to provide the equivalent time in any specified target country and display its time zone.
- The Bootcamp App should be able to generate the Bootcamp schedule in the time/timezone of any country specified.
- **As a bonus,** the app should be able to read the current system time and alert the user if any upcoming bootcamp is less than 24 hours from the current system time.
- Additional bonus: Implement code with a database backend and a graphical user interface.