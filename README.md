# Simple Calculator Android Application

# Author
Mahak Aggarwal

# Features
The application provides basic calculation functionality – addition, subtraction, multiplication, division, modulus, power, and square root in addition to providing buttons for numbers, decimal point, ‘Clear’, and backspace.
It uses string, colour, dimension and style resources. The base layout used in Constraint layout with components like LinearLayout, TextViews, Buttons, and ImageButton. There are two layouts – one for portrait mode and one for landscape mode.
A separate java class is used for the calculation implementation. SavedInstanceState is used to make sure that the data doesn’t clear if the screen is rotated. There is no keyboard input – it is done using the buttons provided on the screen. The following possible errors are considered, and appropriate action is taken –
* Making sure that there is only one decimal point in a number
* The length of the number of characters does not exceed by 10
* The root button works even if there is no first number provided
* Possible division errors

When the backspace button is long pressed, all the contents are cleared. Methods are created and reused to reduce code duplication. Compatibility classes are used to provide backwards compatibility for older android versions.

![App Logo](https://github.com/MahakAggarwal/Android_Simple_Calculator/blob/master/Images/icon_cal.png)

This icon represents the application. Made using Font Awesome Icons and MDBootstrap. It follows material design guidelines.

# Android Specifications
Android Studio Version: 3.1.4
Gradle Version: 4.6
Minimum Android SDK: 19
Target Android SDK: 28

# Screenshots
![Main UI](https://github.com/MahakAggarwal/Android_Simple_Calculator/blob/master/Images/Main%20UI.png)

![Calculation being performed 1](https://github.com/MahakAggarwal/Android_Simple_Calculator/blob/master/Images/Operation%201.png)
![Calculation being performed 2](https://github.com/MahakAggarwal/Android_Simple_Calculator/blob/master/Images/Result%201.png)


# Usage
The usage of the application is self-explanatory. However, the following steps can be followed –
1. Enter a number (up to 10 digits) using the number pad provided
2. Enter an operation using the number pad
3. Enter the second number (up to 10 digits)
4. Press the ‘=’ button to perform the calculation
5. Use the backspace button to delete the last character
6. Enter the first number before entering an operation.
7. Use ‘C’ button to clear all the fields
