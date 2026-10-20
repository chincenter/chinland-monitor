# Chinland Conflict Monitor

Public website of CCPR's monthly monitoring of armed conflict, landmines and drugs in Chinland.

- `index.html` is the dashboard.
- `data/monitor-data.json` is the published data. It is made each month by the CCPR Monitor Converter from the approved workbook. Never upload the workbook itself.
- `data/` also holds the briefing PDFs and cover images named in the workbook's Briefings sheet.
- `data/townships.js` holds MIMU township boundaries for the map.

To update: upload the new files to the `data` folder and commit. The site redeploys automatically.
