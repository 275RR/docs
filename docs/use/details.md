# BB Editor Processes and Workflows

Top directory is **BBeditor** ...

**BB Excel-HTML** is the primary working directory.

**BB Form Editor** directory was created in June 2019 to automate the HTML structure during editing. With "**form###.html**" being the latest version, adding Tom Steichen edits (see ### villages). This editor was granted full copyright to the Burgenland Bunch organization. The form###.html and form.html require the files: form.css form.js

**BB Website (org)** is the original working directory and contains any old files since working on the Surname and Village pages (2019).

**Monthy Backups** is the primary working directory for any backups.

---

1. **BB Excel-HTML** is the main directory for generating every Surname and Village pages ...

2. **output** - theoutput directory containing the files to be uploaded to the BB website

3. **templates** - directory containing all templates and code that uses the data and generates HTML files

4. **#RES #SUR #CHG** - a temporary tracking file used during editing (will be auto-generated in code later)

5. **blue_MasterList.xlsx** - the master data file for _Surnames_ (and the _Member_ List, in-development)

6. **blue_Members.xlsx** - the _Member_ data file copied or separated from the _MasterList_ (currently testing)

7. **blue_Surnames.xlsx** - the _Surname_ data file copied or separated from the _MasterList_

8. **blue_Villages.xlsx** - the _Village_ data file (not copied from _MasterList)_

9. **Command Prompt** - normal MS Windows prompt copied here for testing

10. **run python.bat** - runs the python code on each "blue_" file: Members, Surnames,Villages (The “blue” files are the development code names.)

---

The preferred process steps to edit the MasterList ...

The MasterList has colored header titles:

- Blue are the columns required for the software to create the webpages.
- Red columns are for verification and sorting.
    - Column E, mSorted, was created to keep all the member’s data together.
    - Column C, sSorted, was created to keep all the surnames in its proper order, since new surnames are added to the end of the list.
    - Red columns can be added or deleted to serve other purposes.
    - Column X is for village verification:
        - V = On village pages, 
        - M = That village is only on the map pages,
        - R = Research related and is listed on the rVillages sheet, Blank

Find the new member’s alphabet slot and insert the number of new rows equal to the number of new surnames - plus one Member’s row (highlighted in yellow). The Members row was developed over time to include all the current member’s web data. The Member’s “Other Details” was added after the Members pages were edited by someone else. All to verify any data later.

If a surname is in multiple villages, then duplicate that row and change the village.

Example: B.Agreen has 7 surnames, each in 2 villages, for a total of 14 rows. (It could have 1 surname with 14 different villages.)

The software will interpret duplicate rows and combine them as one table entry with all the villages in one cell. Not a good solution but it works for now.

The process steps to generate the **Excel** files to **HTML** and thus the _Surname_/_Village_ files ...