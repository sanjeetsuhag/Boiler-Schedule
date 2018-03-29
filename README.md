# Boiler-Schedule
[![Build Status](https://travis-ci.org/jackielwu/Boiler-Schedule.svg?branch=master)](https://travis-ci.org/jackielwu/Boiler-Schedule)

## Post Instructions

1. Go to [Google API console](https://console.cloud.google.com/apis/).
2. Go to the Credentials section.
3. Click on Create Credentials button, and select OAuth Client ID from the drop down.
4. Select "Chrome App" as the Application Type.
5. 

## Setup Instructions

1. Download the ZIP file of the repository.
2. Extract the contents of the zipped archive.
3. Open Google Chrome.
4. Go to More Tools > Extensions.
5. On the top right of the page, enable Developer Mode.
6. Click on Load Unpacked.
7. Navigate to the `src/Boiler Sync` folder.
8. Install the extension.
9. Copy the ID of the extension.
10. Go to `src/Boiler Sync/manifest.json` and replace the `key` field's value with your copied ID.
11. Go to [Google API console](https://console.cloud.google.com/apis/).
12. Go to the Credentials section.
13. Click on Create Credentials button, and select OAuth Client ID from the drop down.
14. Select "Chrome App" as the Application Type.
15. Copy the Extension ID in the Application ID field.
16. Copy the generated client ID.
17. Replace the `client_id` field's value with your copied client ID value.

## Usage Instructions

1. Log into MyPurdue.
2. Go to Concise Schedule.
3. Select the current semester.
4. Click on the extension icon.
5. Select which courses you want to add to your Google Calendar.
6. Click Submit.
