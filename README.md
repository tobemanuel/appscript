# AppScript Data Fetchers

This repository contains Google Apps Scripts to fetch data from Notion and Airtable into Google Sheets. It also includes a custom menu for easy access to these functions from the Google Sheets UI.

## Features

- Fetch data from Notion to Google Sheets
- Fetch data from Airtable to Google Sheets
- Custom menu in Google Sheets for easy function access

## Setup

### Notion Data Fetch Script

1. Replace `YOUR_PAGE_ID` and `YOUR_INTEGRATION_TOKEN` in the script with your Notion page ID and integration token.
2. Add the script to your Google Sheets script editor.

### Airtable Data Fetch Script

1. Replace `YOUR_API_KEY`, `YOUR_BASE_ID`, and `YOUR_TABLE_NAME` in the script with your Airtable API key, base ID, and table name.
2. Add the script to your Google Sheets script editor.

### Custom Menu

1. Add the `onOpen` function to your Google Sheets script editor.

## Usage

1. Open your Google Sheets document.
2. Navigate to the `Fetch Data` menu in the toolbar.
3. Select the desired function to fetch data from Notion or Airtable.
