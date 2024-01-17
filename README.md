# About

This is a team roster scheduling template created by me (primarily for VALORANT Premier).\
**NOTE: This spreadsheet was created in Google Sheets. There will be some inconsistencies when using this file in Microsoft Excel.**

## Features
- Dynamic updating for up to 10 roster spots, including player names, substitution status, and schedule
- Schedule listing is both horizontal and vertical (so you don't have to deal with that pesky horizontal scroll bar)
- 'Game Ready?'/'Playing?'/'Subs Available?' status highlights when requirements are met

## Getting Started
1. Download the PREMIER SCHEDULE TEMPLATE.xlsx file.
2. In Google Drive, click on 'New' -> 'File Upload' and upload the file.
3. Populate the spreadsheet with your information. Your schedule, along with other rows, will be updated accordingly.
### Editing the Spreadsheet
**New row insertions for additional roster spots are discouraged, however if you NEED another spot, here are the formulas needed to properly update the spreadsheet:**
- The formula for row 20 under 'Total Available' should have its second cell value updated from ```=COUNTIF(I10:M19, "X")``` to ```=COUNTIF(I10:M20, "X")``` to extend the range of count. This should be repeated for all columns.
- The formula for row 23 under 'Roster' should have ```& IF(I20="X", A20 & CHAR(10), "")``` appended in order to include row 20. This should be repeated for all columns.\
**NOTE: Each column will have different letter prefixes. Please pay attention that you are adjusting the column correctly to line up with the other values in the function.**

## Future Updates
- Improvement on defining 'main' and 'substitute' players on roster listings and schedule
- Agents preferred to determine team composition for each roster lineup for each match day
- Comparison to meta team composition based on map
- History tracker with win percentage of each map, team composition, and player
- Statistics tracker of each player in a 'match report' system

## Want to Help Develop this Project?
- Contact me over Discord: majaslash
- Suggestions? Reach out to me (via Email): xiosoft@hotmail.com

Thanks for reading! <3
