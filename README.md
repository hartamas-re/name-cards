# Name Card Scanner

Mobile-friendly web app for capturing business card photos to Google Drive, logging contact details to Google Sheets, and optionally syncing with Pipedrive.

## Live App
- URL: `https://hartamas-re.github.io/name-cards/`

## Setup Overview
1. **Google Cloud OAuth**: Configure consent screen, test users, and a Web application Client ID with `https://hartamas-re.github.io` as an Authorized JavaScript origin.
2. **Google Drive & Sheets**: Create a Drive folder for card photos and a Google Sheet with `Users` and `Cards` tabs.
3. **Google Apps Script**: Deploy `Code.gs` as a Web App (`Execute as: Me`, `Who has access: Anyone`).
4. **GitHub Pages**: Host `index.html` from the `main` branch (`/ (root)`).
