**#Password-Generator** <br>

🌟**Project Overview**<br>
The Password Generator is a web-based tool that enables users to create strong, random passwords. Users can specify the desired length and choose which character types (uppercase, lowercase, numbers, symbols) to include. The generated password can be copied to the clipboard with a single click.<br>

🌟**Project Structure**<br>

_The project consists of three main components_<br>

1 **HTML:** Defines the structure and content of the webpage and sets up the basic layout of the Password Generator interface.<br>
2 **CSS:** Styles the visual appearance of the webpage and the elements of the Password Generator, ensuring a visually appealing and user-friendly interface.<br>
3 **JavaScript:** Implements the functionality for generating and copying passwords.<br>

🌟**Explanation:**<br>
_JavaScript script.js_<br>

◾ Element Selection: document.getElementById() retrieves the HTML elements that are manipulated by JavaScript.<br>

◾ randomFunc Object: Holds functions to generate random characters for each type (lowercase, uppercase, number, symbol).<br>

◾ Clipboard Functionality:<br>
clipboardEl.addEventListener('click', () => { ... }): Adds an event listener to the copy button to copy the generated password to the clipboard.<br>
Creates a textarea to temporarily hold the password, selects the text, copies it, and then removes the textarea.<br>

◾ Password Generation:<br>
generateEl.addEventListener('click', () => { ... }): Adds an event listener to the generate button to create a new password.<br>
Calls the generatePassword function with the selected settings.<br>

◾ generatePassword() Function:<br>
Builds the password by iterating over the selected character types and appending random characters until the desired length is reached.<br>
Returns the final password string.<br>

◾ Random Character Functions: Generate random characters for lowercase, uppercase, numbers, and symbols using character codes and arrays.<br>

🌟**How to Run the Project**<br>
1 Download the Files: Ensure all the project files (index.html, style.css, script.js) are saved in the same directory.<br>
2 Open index.html: Double-click on index.html to open the password generator in your default web browser.<br>
3 Adjust Settings: Use the checkboxes and number input to select your password preferences.<br>
4 Generate Password: Click the "Generate" button to create a password.<br>
5 Copy to Clipboard: Click the "Copy" button to copy the generated password to the clipboard.<br>

🌟**Conclusion**<br>
The Password Generator project is a simple yet practical application demonstrating the use of HTML for structure, CSS for styling, and JavaScript for functionality. It provides users with a tool to generate secure passwords based on their specified criteria and copy them for easy use.<br>
