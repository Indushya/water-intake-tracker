1. Overview of the Project
   
WaterLog is a personal tracking application designed to help users monitor and manage their daily water intake. The project's goal is to promote better hydration habits by providing an easy way to log water consumption, set personalized daily goals, and visualize progress against those goals. This implementation serves as an application of the subject concepts learned in the course. 

3. Features
The WaterLog tracker provides the following core features:


Intake Logging: Allows users to record water intake with volume and time.

Goal Setting: Users can define a personalized daily water intake target.

Progress Dashboard: A visualization (e.g., a progress bar or percentage) showing how close the user is to hitting their daily goal.

Historical Analytics: Provides a summary of past intake data, such as daily/weekly average intake and goal consistency.


CRUD Operations: Ability to Create, Read, Update, and Delete individual water intake entries.

3.  Technologies and Tools Used
   
   python language : used for the core application logic
   
github :required for source code management and submission

4. Steps to Install & Run the Project
   
The steps required to set up and run the project are as follows:

Prerequisites

Ensure Python 3.x is installed on your system.

Ensure Git is installed for cloning the repository.

5. Instructions for Testing

Testing ensures the application meets its functional and non-functional requirements.


 Input Validation Test:

Attempt to log a volume of 0 or a negative number. The system must reject the input and provide a clear error message (meeting the Error handling strategy requirement).


Attempt to log non-numeric text. The system must reject the input.

Logging & Goal Progress Test:

Set a daily goal (e.g., 2000 ml).

Log multiple entries (e.g., two entries of 500 ml).

Verify the Progress Dashboard accurately shows 50% completion.

Data Persistence Test:

Log several water entries.

Close and restart the application.

Verify all previously logged entries are correctly loaded, demonstrating Reliability.
