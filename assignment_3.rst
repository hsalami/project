.. |srarr|    unicode:: U+02192 .. RIGHTWARDS ARROW

Excel Assignment - Tabular Data
--------------------------------------------


**PRACTICUM [GROUP]** - Take 30 minutes to answer the following questions. Once you have finished we will ask for volunteers and discuss responses as a group.


A) Import the music_raw_data.txt file into Excel.

   Answer: Click File |srarr| Open |srarr| Browse. A new window will open showing files and directories. Switch the dropdown menu above the "Open" button to "All Files", select music_raw_data.txt and press open. Select "Delimited" and "My Data Has Headers" and click "Next". Then Select "Comma" and "Next".

B) Resize the columns in the spreadsheet to improve visibility.

   Answer: Highlight all columns and double click on the border between any two columns.

C) Remove all blank rows from your spreadsheet.

   Answer: Highlight all columns and go to Home |srarr| Editing Group |srarr| "Find & Select".  From the dropdown menu click on "Go to Special" and check "Blanks". The blank rows in the table will be highlighted. Right click on any of the highlighted rows and select "Delete" and "Shift Cells Up".

D) Remove the leading and trailing spaces in the "Artist" column.

   Answer: Insert a new column to the right of the "Artist" column. Type in ``=TRIM(C2)`` into cell ``D2`` in the new column. Press "Enter" then double click on the small green rectangle on the bottom right of the cell highlight to propagate to all rows.

E) Force all the words in the "Artist" column to start with a capital followed by lower case letters.

   Answer: Insert a new column to the right of column D. Type in ``=PROPER(D2)`` into cell ``E2`` in the new column. Press "Enter" then double click on the small green rectangle on the bottom right of the cell highlight to propagate to all rows.
     
   Or 
     
   Insert a new column to the right of the "Artist" column. Type in ``=PROPER(TRIM(C2))`` into cell ``D2`` in the new column. Press "Enter" then double click on the small green rectangle on the bottom right of the cell highlight to propagate to all rows.

F) Hide or remove the redundant column(s) that duplicate the "Artist" column to leave only the column that is both TRIM and PROPER visible.

   Answer: Hide the column(s) by highlighting the column(s) you wish to hide, right clicking on the column(s) and selecting "Hide" from the menu.
     
   Or 

   Copy the TRIM and PROPER Column and Paste Special (Values Only) into column "C" follow up by deleting all redundant columns.

G) Replace "Hard Rock" with "Rock" in the "Genre" column.

   Answer: Hold Ctrl and press F. Click the "Replace" tab and input "Hard Rock" into "Find What", and "Rock" into "Replace With", then click "Replace All".

H) Remove all duplicate rows from the table.

   Answer: Highlight all columns in the table and navigate to Data Ribbon |srarr| Data Tools then click on the "Remove Duplicates" icon click "Select All" and then "Okay".
