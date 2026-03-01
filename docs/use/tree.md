# BB Editor Directory Tree

```text
BB-Editor-V3-main/
├── App/
│   ├── .streamlit/
|   │   ├── modules/                    (app function library)
|   │   │   └── config.py
|   │   │   └── convert_member_to_html.py
|   │   │   └── convert_surname_to_html.py
|   │   │   └── convert_village_to_html.py
|   │   │   └── email_dropdown_data.py
|   │   │   └── email.py
|   │   │   └── ftp.py
|   │   │   └── github.py
|   │   │   └── zip.py
|   │   ├── pages/                      (app webpages)
|   │   │   └── settings_backup.py
|   │   │   └── settings_email.py
|   │   │   └── settings_ftp.py
|   │   │   └── settings_github.py
|   │   │   └── tools_BBeditor.py
|   │   ├── temp/                       (app temp email files for Monthly Backups)
|   │   ├── defaults.toml               (default app settings)
|   │   ├── secrets.toml                (private user app settings)
│   ├── templates/
│   │   └── Jinja templates to create BB webpages
│   ├── webpages/                       (file/folder structure as on BB website)
│   │   ├── Chroniks/
│   │   │   └── BB village history
│   │   ├── CommonFiles/
│   │   │   └── BB website webfiles
│   │   ├── Members/
│   │   │   └── BB Members webfiles
│   │   ├── Surnames/
│   │   │   └── BB Surnames webfiles
│   │   ├── Villages/
│   │   │   └── BB Villages webfiles
│   │   ├── .htaccess
│   │   └── bb.ico
│   ├── 04 Res - 07 Sur - 02 Chg.file   (Note for the New section on Surnames Homepage)
│   ├── BBeditor.py                     (entry point for Streamlit app)
│   ├── blue_MasterList.xlsx
│   ├── blue_Members.xlsx
│   ├── blue_Surnames.xlsx
│   ├── blue_Villages.xlsx
│   └── Run BBeditor.bat                (**START HERE** - calls BBeditor.py)
├── Monthly Backups/
│   └── Zip Archive of the App folder
├── Tutorial/
│   └── Files and images                (used by this README.md)
├── .gitignore                          (files/folder to ignore when push to Github)
├── .python-version                     (for uv package manager)
├── README.md
├── Read Me.rtf
├── install-git.ps1                     (git install helper script)
├── pyproject.toml                      (for uv package manager)
└── uv.lock                             (for uv package manager)
```
