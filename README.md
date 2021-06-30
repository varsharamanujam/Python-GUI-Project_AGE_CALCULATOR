# Python-GUI-Project_AGE_CALCULATOR

This python code is executed using pycharm.

The following steps explains flow of the code.

Step 1: Import the tkinter module and datetime module.

Step 2:  Creating a window named as App - i.e(App=Tk()),geometry and background color of the application is set as well.

Step 3: Add .ico file to resources as shown and make it as logo for the application.

Step 4: "Enter your DOB" text is displayed using label and alligned using grid() method. 

Step 5: Label and Entry widget feild for Date, Month and year is created and then aligned using grid() method.

Step 6: Create a function to find no.of days lived. -> Datetime keywork is used to find DOB -> datetime.now() is then used to find the present date time and the difference in days is then displayed and aligned using grid() method.

Step 7: Create a another function to find no.of seconds lived. -> Datetime keywork is used to find DOB -> datetime.now() is then used to find the present date time and the difference in days -> total_seconds() method is then used to keep seconds updated, then the seconds is displayed and aligned using grid() method.

Step 8: Create variables for for total no of buttons and as align them. 

Step 8: Use the command App.mainloop() to execute the above written code.

note- * You can use the pack() method instead of using grid() method also, but using grid() method is prefered*
