# Instructions to Download and Configure the Database

This repository contains a file that you can download to set up your local database. Follow the steps below to get started:

## Downloading the File

1. Click on the green "Code" button at the top right corner of this page.
2. Select "Download ZIP" to download the entire repository as a ZIP file.
3. Unzip the downloaded file on your computer.

## Configuring the .env File

To connect your local database, you'll need to set up a `.env` file. Follow these steps:

1. Open the `example.env` file located in the root of the repository.
2. Copy the contents of `example.env`.
3. Create a new file named `.env` in the root of the repository.
4. Paste the copied content into the `.env` file.
5. Fill in the environment variables with your local database information. For example:

DB_HOST=localhost
DB_USER=your_username
DB_PASSWORD=your_password
DB_NAME=your_database_name


Then in web exec npm run dev:next
Then in back exec npm run start:serverv2