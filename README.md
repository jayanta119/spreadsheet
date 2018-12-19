You can use worksheet position number (1 for the first/default worksheet, 2 for the second worksheet).

Original answer

I came across the same issue and I managed to find my way out. It seems that they recently changed the id for each worksheet.

You can find the new ID at the following

https://spreadsheets.google.com/feeds/worksheets/YOUR_SPREADSHEET_ID/private/full

I got something like o3laxt8 between <id> tags

Ps: od6 anddefault values will always work and redirect to the first worksheet of your document.

Joe Germuska' note:
