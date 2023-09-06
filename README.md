# replace_color_apps_script
This GitHub repository contains a set of Google Apps Script functions designed to automate the process of replacing text color within a Google Docs document.
The code consists of two main functions:

onOpen(): This function creates a custom menu in Google Docs labeled "Replace," which provides a user-friendly way to trigger the text color replacement process.

replaceTextColor(): When invoked through the custom menu, this function scans the entire document's text and identifies instances of a specified original color (in this case, red) and replaces it with a new color (in this case, blue). It also logs the index of each character where the color change occurs.

This script can be useful for scenarios where you need to make systematic text color adjustments in a Google Docs document, such as changing specific elements to match a consistent color scheme or highlighting certain content.

Feel free to clone or fork this repository to use the code in your own Google Docs projects or contribute to its development. If you have suggestions or encounter issues, please open an issue or submit a pull request to collaborate with the community and enhance this functionality further.
