# Job Application Tracker

A professional web application for tracking job applications, designed specifically for managing both workplace redeployment opportunities and personal job searches.

## Features

- **Comprehensive tracking** of job application details including:
  - Job vacancy number
  - Job title
  - Employer
  - Salary
  - Job description
  - Closing date
  - Application status with dates
  - Assessment and interview schedules
  - Custom CV storage
  - General notes
- **Differentiate** between workplace redeployment applications and personal job searches
- **Export** workplace redeployment applications as Excel (xlsx) files
- **Filter** applications by date range
- **Professional interface** with neon blue theme
- **Secure** - all data stored locally in your browser
- **UK English** spelling throughout

## How to Use

The application is available in two formats:

### Option 1: All-in-One HTML File (Recommended)

Simply open the `all-in-one.html` file in any modern web browser. This standalone version contains all HTML, CSS, and JavaScript in a single file.

### Option 2: Separate Files

If you prefer a modular approach, you can use the separate files:
- `index.html` - The main structure
- `styles.css` - The styling
- `app.js` - The functionality

These files must be kept in the same directory.

## Live Demo

You can access a live version of this application at: [https://yourusername.github.io/job-application-tracker/all-in-one.html](https://yourusername.github.io/job-application-tracker/all-in-one.html)

## Data Storage

This application uses your browser's local storage to save your data, meaning:
- No data is sent to any server
- Your information stays private on your device
- Data persists between browser sessions
- Clearing browser data will erase your saved applications

## Export Features

When exporting workplace redeployment applications:
- Only applications marked as "Workplace Redeployment" will be included
- Date filtering allows you to specify the exact date range for reporting
- Exports include all relevant fields required for reporting to management

## Browser Compatibility

Works best with modern browsers including:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

## Development

This application is built with vanilla JavaScript, HTML, and CSS. No frameworks or libraries are required except for the SheetJS library for Excel export functionality, which is loaded from a CDN.

## License

This project is available for personal use.

## Acknowledgements

- [SheetJS](https://sheetjs.com/) for Excel file export functionality
