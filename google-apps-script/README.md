# Apps Script Folder

Paste these files into the Apps Script project attached to the nutrition Google
Sheet. Leave `SPREADSHEET_ID` blank when the script is spreadsheet-bound.

Run `setupDatabase` from the spreadsheet menu before deploying. The script uses
SpreadsheetApp for data, CacheService for reduced reads, DocumentApp for report
layout and DriveApp for PDF storage.
