# CSV MERGER

This script allows you to merge contacts from two CSV files and remove redundant contacts. Follow the instructions below to download your CSV contacts from your Google account and use them with this Python script.

## Downloading CSV Contacts from Google Account

1. Go to [Google Contacts](https://contacts.google.com/) and sign in to your Google account.
2. In the left sidebar, click on "Export".
3. Select the contacts you want to export or choose "All contacts" if you want to export all of them.
4. Choose the "Google CSV" format.
5. Click on the "Export" button and save the file as `contacts1.csv` and `contacts2.csv` respectively.

## Running the Script

1. Make sure you have Python installed on your computer. You can download Python from the official website: [https://www.python.org/downloads](https://www.python.org/downloads).
2. Save the [merge_contacts.py](merge_contacts.py) script to your computer.
3. Move the downloaded `contacts1.csv` and `contacts2.csv` files to the same directory as the `merge_contacts.py` script.
4. Open a command prompt or terminal and navigate to the directory where the script and CSV files are located.
5. Run the following command to execute the script: python merge_contacts.py

6. After the script finishes executing, a file named `merged_contacts.csv` will be created in the same directory, containing the merged contacts with no redundancies.

That's it! You have successfully merged your CSV contacts using the Python script.

Feel free to customize the script and experiment with different CSV files to meet your requirements.

Note : This script was created when no contact apps provided this service this can still be used to do something other than what it is ment for cheers.
