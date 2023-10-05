# Web Scraping of Interpol Red Notices

This project consists of a web scraping application that extracts information from Interpol's Red Notices using the Interpol's public API. Red Notices are international notifications issued by Interpol for individuals sought by law enforcement authorities worldwide.

# Objective

The objective of this project is to gather detailed information about Interpol's Red Notices, including details about the individuals sought, such as name, date of birth, and nationalities. The collected information is stored in an Oracle database for record-keeping and analysis purposes.

# Prerequisites

Before running the project, ensure that you have installed the following Python libraries:

requests: To make HTTP requests to the Interpol API.
beautifulsoup4: To parse the HTML of the API page and extract information.
json: To handle the JSON data returned by the API.
cx_Oracle: To connect to and interact with the Oracle database.

# Results
The collected data is stored in a table called IDWALLTESTE in the Oracle database. The table has columns for the person's name, date of birth, and nationalities.

# Contributions
Contributions are welcome! If you wish to improve this project or add additional features, please feel free to open a pull request with your changes.


