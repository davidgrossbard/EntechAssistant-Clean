========================================
ENTECHASSISTANT REPORT SYSTEM
========================================

WHAT'S INCLUDED:
- index.html    : The main application
- data.js       : Your building data
- README.txt    : This file

========================================
HOW TO USE:
========================================

1. Make sure both files are in the same folder:
   - index.html
   - data.js

2. Double-click index.html to open in your browser

3. Search or browse for any management company

4. Click "Generate Report" to create their presentation

5. Navigate through the report using:
   - Arrow buttons (← →)
   - Dropdown menu (for large portfolios)
   - Page dots (for small portfolios)

========================================
SYSTEM REQUIREMENTS:
========================================

- Any modern web browser (Chrome, Edge, Safari, Firefox)
- No internet connection needed after initial load
- Works on Windows, Mac, or Linux
- Works on tablets (iPad, Surface, etc.)

========================================
TO UPDATE DATA:
========================================

IMPORTANT: Use the Python converter script (convert_csv_to_js.py) to ensure
proper data formatting and prevent display issues.

1. Put convert_csv_to_js.py in the same folder as your CSV
2. Double-click it (or run: python convert_csv_to_js.py)
3. It creates data.js with properly formatted data
4. Refresh your browser

Alternative manual method:
1. Export your new CSV data as JSON format
2. Open data.js in any text editor
3. Replace the array with your new data
4. Make sure TotalDiscByp values are numbers, not strings
5. Save the file
6. Refresh your browser

========================================
TROUBLESHOOTING:
========================================

"Data Not Found" Error:
- Make sure data.js is in the same folder as index.html
- Check that data.js contains your building data
- Try refreshing the browser (Ctrl+F5 or Cmd+Shift+R)

Slow Performance:
- Close other browser tabs
- Try Chrome or Edge for best performance
- For very large portfolios (100+ buildings), allow a few seconds to load

========================================
TIPS FOR SALES TEAM:
========================================

- Use arrow keys on keyboard for quick navigation
- Press F11 for full-screen presentation mode
- The dropdown shows offline days for each building
- Focus on buildings with high downtime first
- Management summary shows portfolio totals

========================================
SUPPORT:
========================================

For technical issues or questions, contact your IT department.

To request new features or report bugs, email: [your-email@company.com]

========================================
Version 1.0 - EntechAssistant Report System
========================================