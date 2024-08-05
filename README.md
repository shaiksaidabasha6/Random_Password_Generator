# Password Generator

## Overview

This Password Generator is a simple web application built using HTML, CSS, and JavaScript. It allows users to generate random passwords according to their preferences, including password length and character types (uppercase letters, lowercase letters, numbers, and symbols). The generated password can be copied to the clipboard with a single click.

## Features

- **Customizable Password Length**: Users can specify the length of the generated password.
- **Selectable Character Types**: Users can choose which character types to include in the password (uppercase letters, lowercase letters, numbers, symbols).
- **Random Password Generation**: The application generates random passwords based on the user's preferences.
- **Responsive Design**: The application is designed to be responsive and compatible with various screen sizes.


## How to Use

1. **Open the Password Generator Website**:
   - Navigate to the URL where the Password Generator website is hosted.

2. **Adjust Password Length**:
   - Use the slider labeled "Password Length" to specify the desired length of the generated password. The length can be adjusted from a minimum value to a maximum value.

3. **Select Character Types**:
   - Check or uncheck the checkboxes labeled "Include Uppercase letters," "Include Lowercase letters," "Include Numbers," and "Include Symbols" based on the character types you want to include in the generated password. You can include any combination of these character types.

4. **Generate Password**:
   - Click the "Generate Password" button to generate a random password based on your preferences. The generated password will be displayed in the designated area on the website.

5. **Generate Another Password**:
   - If you're not satisfied with the generated password, you can adjust the settings and click the "Generate Password" button again to generate a new password.

6. **Responsive Design**:
   - The Password Generator website is designed to be responsive and compatible with various screen sizes, allowing you to use it on desktop, tablet, and mobile devices seamlessly.



## JavaScript Functions and Properties:

### JavaScript Functions:

1. **generateRandomInteger()**:
   - This function generates a random integer between 0 and 9.

2. **generateLowerCase()**:
   - This function generates a random lowercase letter.

3. **generateUpperCase()**:
   - This function generates a random uppercase letter.

4. **generateSymbols()**:
   - This function selects a random symbol from the predefined `symbols` string.

5. **handleSlider()**:
   - This function updates the displayed password length based on the position of the slider and adjusts the background size of the slider accordingly.

6. **handleCheckBoxChange()**:
   - This function is called when any checkbox (uppercase, lowercase, numbers, symbols) is checked or unchecked. It updates the count of checked checkboxes and adjusts the password length if necessary.

7. **shufflePassword(array)**:
   - This function shuffles the characters of the generated password using the Fisher-Yates shuffle algorithm.

### JavaScript Properties:

1. **password**:
   - This property holds the generated password.

2. **passwordLength**:
   - This property represents the desired length of the generated password.

3. **checkCountor**:
   - This property stores the count of checked checkboxes.

4. **symbols**:
   - This property is a string containing predefined symbols used for generating passwords.

These functions and properties are integral to the functionality of the Password Generator, enabling the generation of random passwords based on user preferences and enhancing the security of generated passwords by including various character types.



## Credits

This Password Generator project was created by Gaurav Kumar. The project was developed after watching a tutorial video by LOVE BABBAR in Dot Batch. The following technologies and resources were used in the development of this project:

- HTML
- CSS
- JavaScript

---

