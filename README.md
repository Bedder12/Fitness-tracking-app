# St8tus4U's Clock - Fitness Tracker Application

The St8tus4U's Clock project is a fitness tracking application developed to visualize and analyze training data gathered from the St8tus4U fitness watch. The app provides users with an intuitive interface to track their outdoor activities, such as running, cycling, or hiking, and visualize key parameters like heart rate, speed, altitude, and distance. The app also supports importing CSV files, saving activities, and offering statistical insights into each training session.

# Features

- Login System: User authentication using username and password.
- Activity Management: Import and save training activities with customizable names and dates.
- Data Visualization: Graphical representations of heart rate, speed, and altitude using dynamic charts.
- Map Visualization: View the route of an activity on a map based on latitude and longitude data.
- Statistics Panel: Display statistics such as total distance, maximum, minimum, and average speed and heart rate.
- Persistent Storage: Data is saved and loaded between sessions for continuous tracking.

# System Architecture
The application follows the Model-View-Controller (MVC) design pattern, ensuring separation of concerns and promoting modularity. The program consists of the following components:

- Model: Manages and stores activity data. Key classes include Activity, ActivityManager, TrackPoint, and TextAnalyzer.
- View: Handles the user interface, with classes like UserGUI, MapGUI, and PlotGUI.
- Controller: Acts as the intermediary between the model and the view, managing user input and updating the view accordingly.

# How to Run the Program
Prerequisites
- Java Development Kit (JDK) installed
- Java IDE (e.g., IntelliJ IDEA, Eclipse)

# Steps to Run the Application
1. Download and Extract Files:
- Download the ZIP file containing the project files and data CSV files.
- Extract the contents to a folder on your machine.

2. Set Up CSV Files:
- Place the CSV files activities.csv and trackPoints.csv in an accessible folder.

3. Open the Project:
   Open the project in your Java IDE.
   
4. Configure File Paths:
- Modify the file path in the Controller class to point to the location where the CSV files are stored.

5. Run the Program:
- Execute the Main class to start the application.

Example of Use

Login: Enter the username and password to access the app.
User Authentication: Users log in via a simple GUI interface.
![Screenshot 2024-12-06 at 02 54 52](https://github.com/user-attachments/assets/93ac1a18-4923-442a-850c-b0e8234d6afe)

Data Management: Training data is imported via CSV files and organized by activities, which are user-defined with custom names and dates.

Import a CSV File: Use the “Import CSV” button to load a training session, enter the activity’s name and date.

* A Map Panel for plotting the training routes based on GPS data (latitude and longitude).
![Screenshot 2024-12-06 at 03 04 40](https://github.com/user-attachments/assets/6d231a12-0cf2-4765-8526-bd0462dfb1d3)

View the Activity: Once imported, you can select the activity from a list and view detailed statistics in both tabular and graphical formats.


* A Plot Panel displaying time-series graphs for heart rate, speed, and altitude.
![Screenshot 2024-12-06 at 03 08 44](https://github.com/user-attachments/assets/bf8897ab-6083-492b-a7db-7ad25975d006)

Map and Plot: See the path of the activity on the map and visualize metrics like heart rate, speed, and altitude through dynamic plots.


* A Statistics Panel that presents key metrics like total distance, average and maximum heart rate, speed, and altitude.
![Screenshot 2024-12-06 at 03 11 16](https://github.com/user-attachments/assets/4330914e-9cdb-41eb-b3cc-411cf1908ca1)




