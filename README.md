# SOFTDEV2_Lab-Activity-1
Our Lab Activity 1 in Software Development 2

Basically, the instruction is to: 

This lab focuses on core concepts and can be readily expanded for a richer experience.

Objectives
Learn to structure an Android Studio project.
Understand the use of basic UI components: TextView, EditText, and Button.
Implement simple user input and display.
Prerequisites
Android Studio installed and configured.
Basic understanding of XML layouts.
Familiarity with Java programming concepts.
Lab Activity
1. Project Creation
Start a new Android Studio project:
Open Android Studio and select "Start a new Android Studio project".
Choose "Empty Activity" as the project template.
Give your project a suitable name (e.g., "MyPortfolioApp").
Select Java as the programming language.
2. Design the Layout (activity_main.xml)
Open the activity_main.xml file (under app -> res -> layout).

Switch to the "Design" view.

Add the following components from the "Palette" section:

TextViews:
Place TextViews for labels like "Name", "Email", "Phone Number", "About Me".
EditTexts:
Place EditText fields next to the corresponding labels to allow the user to input their information.
Button:
Add a Button labeled "Save".
Arrange the components:

Use a layout like LinearLayout or ConstraintLayout to organize the components neatly. Consider a vertical LinearLayout for simplicity.
3. Implement the Logic (MainActivity.java)
Open the MainActivity.java file.

Declare variables for UI components:

Initialize the variables in the onCreate() method:

Add a click listener to the save button:

4. Run the App
Connect an Android device or start an emulator.
Click the "Run" button in Android Studio. The app will be built and installed on your device/emulator.
5. Test and Experiment
Enter information into the EditTexts.
Click the "Save" button to view your input on the TextViews.
Try modifying the layout for better presentation.
Extensions
Add more fields: Include fields for address, skills, website, etc.
Styling: Customize the look and feel with colors, fonts, and themes.
Image: Add an ImageView to allow the user to include a profile picture.
Data persistence (OPTIONAL): Use SharedPreferences or a simple database (like Room) to save the entered information.
