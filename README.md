# JavaScript Coding Challenge 

## Problem Statement
Create a small web application that can access an external service to retrieve stock information and present it to the user. The information should be presented in a table and have a set of controls for managing retrieval, updating, and clearing of the data in this table.
## Project Details & Constraints
- The challenge must be completed in HTML and JS, and submitted as a .html file.
- You may use any design patterns and libraries you deem necessary to accomplish this task.
- The specific requirements section lists the visual and functional requirements. You may have any composition of elements and work behind the scenes you deem necessary. 

## Specific Requirements
- The app should display all inputs, all buttons, and the table upon load. The table should start empty.
- The table should have columns for the stock symbol, the price, and the GMT date and time the price was retrieved.
- The external service to access is:
    - http://candidateservices.southcentralus.cloudapp.azure.com/randomQuote/quote?symb ols=&lt;symbols go hereid&gt;
- The app should contain these buttons and inputs:
    - A text input that will hold input of a comma-delimited list of stock symbols.
    - An update button that will immediately query the service with the input stock symbols and add the results to the beginning of the table.
    - A clear history button that will remove all existing records from the table. It should not remove the table header.
    - A drop down for selecting an auto-update interval. This should have the options of 2, 5, 10, and 30 seconds.
    - A button to start and stop automatic updates. If automatic updates are in progress, this button being pressed again should stop the automatic update and the text of the button should indicate it will do that. - A second ticker that counts down until the next update. ○ A label above the table indicating the last (local) time an update was pushed to the table. 