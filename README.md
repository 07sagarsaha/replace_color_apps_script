# replace_color_apps_script
This GitHub repository contains a set of Google Apps Script functions designed to automate the process of replacing text color within a Google Docs document.
The code consists of two main functions:

onOpen(): This function creates a custom menu in Google Docs labeled "Replace," which provides a user-friendly way to trigger the text color replacement process.

replaceTextColor(): When invoked through the custom menu, this function scans the entire document's text and identifies instances of a specified original color (in this case, red) and replaces it with a new color (in this case, blue). It also logs the index of each character where the color change occurs.

This script can be useful for scenarios where you need to make systematic text color adjustments in a Google Docs document, such as changing specific elements to match a consistent color scheme or highlighting certain content.

Feel free to clone or fork this repository to use the code in your own Google Docs projects or contribute to its development. If you have suggestions or encounter issues, please open an issue or submit a pull request to collaborate with the community and enhance this functionality further.


How to Use:

Follow these steps to utilize the provided Google Apps Script functions for text color replacement within a Google Docs document:

Clone or Download the Repository:

Start by cloning this GitHub repository to your local machine using Git or download it as a ZIP archive. Alternatively, you can create a new Google Apps Script project in Google Docs and copy-paste the code.
Access Your Google Docs Document:

Open the Google Docs document in which you want to perform text color replacement.
Open the Script Editor:

Within Google Docs, go to Extensions > Apps Script. This will open the Google Apps Script editor.
Paste the Code:

If you've cloned the repository, open the Code.gs file and copy its contents. If you downloaded the ZIP archive, open the Code.gs file from the extracted folder. Paste the code into the Google Apps Script editor, replacing any existing code.
Save and Run:

Save your project in the Google Apps Script editor. You can provide a project name if prompted.
Configure the Custom Menu:

In the script editor, click on the "Select function" dropdown (located near the run button) and choose "onOpen." Then click the run button. This will execute the onOpen function, creating a custom menu labeled "Replace" in your Google Docs document.
Trigger Text Color Replacement:

In your Google Docs document, you will now see a "Replace" menu. Click on it and choose "Character conversion (orgcolor→newcolor)." This will execute the replaceTextColor function, which will scan the document for text with red color and replace it with blue.
View Log (Optional):

As the script runs, it will log the index of characters where the color change occurs. You can view these logs in the Google Apps Script editor by clicking View > Logs.
Adjust Color Parameters (Optional):

You can modify the org_color and replace_color variables in the code to specify different colors for replacement. Simply replace the color codes with the desired hex color codes.
Save and Reuse:

Save your changes in the Google Apps Script editor for future use. You can return to your Google Docs document's "Replace" menu anytime to perform additional text color replacements.
By following these steps, you can easily use the provided script to automate text color replacement in your Google Docs documents.
