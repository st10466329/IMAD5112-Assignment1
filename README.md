Assignment 1: IMAD 
This android app is a fixed menu that recommends healthy/fresh food due to the day of time, the name of the app is Hood Flavor it is meant to assist a customer by suggesting meals.
Specific Functionality:
When the user enters a time and clicks "submit":
If no input is given, shows a toast message "Please Enter a Time of Day."
For valid times, displays meal suggestions like:
Morning: Breakfast options
Mid-morning: Snack options
Afternoon: Lunch options
Mid-afternoon: Snack options
Dinner: Main course
After dinner: Dessert
For invalid times, shows a message asking for valid input
The reset button currently just shows a "Menu reset" toast
Technical Details:
Written in Kotlin for Android
Uses basic Android components:
EditText for input
Button for actions
TextView for displaying suggestions
Toast for messages
Follows the Model-View-Controller pattern with activity handling both view and controller roles
The app is simple but could be expanded with more meal options, images, or integration with actual time of day.
