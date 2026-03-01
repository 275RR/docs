# Burgenland Bunch Editor v3

### Improved Workflow for Village and Surname Editors

The BB Editor v3 is a collection of tools all in one easy to use app.  
The app simplifies and/or automates the editor process of making changes to the webpages on the BB website.

- [Burgenland Bunch](https://www.the-burgenland-bunch.org/)
- [BB Editor Code](https://github.com/275RR/BB-Editor-V3)

### Old Way vs New Way

Members submit new data and/or changes. The editor looks through the html files (which are numerous and long) and inserts the changes directly into the webpages. This process is straight-forward and requires low technical knowledge. However, this process is highly prone to errors, tedious, and difficult to understand changes at a macro level.

Now, the editor uses Excel to insert changes into the Village and Surname data. Next, the editor uses BB Editor v3 (a simple GUI tool) to manage version control and to convert the Excel data into webpages, backup data, and upload the new webpages to the BB website. Although, this code does create technical debt.

*However, since the end result is the same using either method (old or new), an editor could use the Old Way at any time if needed.*

Some new features:

1. uses Excel as a light database
2. Excel for its data entry tools
3. builds webpages from Excel data using templates
4. new webpage design with mobile support
5. backup editor files and data
6. upload webpages to BB website
7. push/pull this project to GitHub
