# Street_Manager-Coordination_Stats
Template Spreadsheet for determining Coordination Statistics (Excel)

This spreadsheet is used to monitor staff utilisation of Street Manager, for those using Street Manager, from a Highway Authority (HA), as their primary input to Street Manager.  There are many facets to Street Manager and the sheet may not capture them all.  It is intended purely as a guide for interaction to determine if any training or support may be required and should not be used as definitive proof of interaction with the system, particularly if an API is also used, as interactions using the API will not be recorded in the users own name.


Very little setup required:

1. Amend the Names and associated Emails in the "Config" tab.  This must be the email used for permit assessment within Street Manager, emails are often not the same via API software.

2. Select "Download All My Data" on Street Manager and open the "Audit" export spreadsheet in the created zip file.  Copy and paste the content, from the Audit spreadsheet, onto the tab, on the Coordination spreadsheet, labelled "Audit Export", from cell A1.  Subsequent exports can be added in the last free row, from the A column, if wishing to add more data to the sheet. e.g. if the next free column is A374, then copy and paste the new data from cell A374.

3. This will auto populate both the "Monthly (Stats)" and "Weekly (Stats)" tabs.  Weekly stats attempt to separate statistics by weeks (Monday - Sunday), should the month begin mid-week, or later week, week 1 will take this as the first day and attempt to end the week on the next Sunday.

