# Lead Generation and Email Outreach Automation

This Python script automates the process of lead generation from Google Maps, data management in a CSV file, personalized email content generation, and email sending using an SMTP server.

## Features

- Scrapes business information from Google Maps.
- Manages lead data in a CSV file.
- Integrates with Google Sheets for data management.
- Generates personalized email content using ChatGPT API.
- Sends personalized emails using an SMTP server.

## Prerequisites

Before running the script, make sure you have the following:

- Python installed (version X.X.X)
- API keys for Google Maps, OpenAI ChatGPT, and your chosen email service provider.

## Setup

1. Clone this repository to your local machine.

2. Install the required Python libraries by running:

```bash
pip install openai

```



##  Add your API keys and credentials
1. Replace YOUR_GOOGLE_MAPS_API_KEY, YOUR_OPENAI_API_KEY, YOUR_EMAIL_SERVICE_API_KEY, smtp.example.com, your_email@example.com, and your_email_password in the script.

## Add your own API key values into `config/api_keys` as follows:   

Obtain and place your Google Sheets API credentials in a file named credentials.json in the project directory.

## Usage
Open a terminal or command prompt.

Navigate to the project directory:

```bash
cd lead_generation_project
```
1. Run the script:
```bash
python lead_generation.py
```
The script will execute the lead generation process, manage data, generate personalized emails, and send them using your specified SMTP server.

## Instructions
### Google Maps API Key:

>Get your Google Maps API key from the Google Developer Console.

>Replace YOUR_GOOGLE_MAPS_API_KEY in the script.
### OpenAI API Key:

>Obtain an API key from OpenAI.

>Replace YOUR_OPENAI_API_KEY in the script.

### Email Service API Key:

>Choose an email service provider and obtain an API key.

>Replace YOUR_EMAIL_SERVICE_API_KEY in the script.

### SMTP Server Configuration:

>If you're using an SMTP server, replace smtp.example.com with your SMTP server address, and provide your email and password.

### Google Sheets Integration:

>Create a new project in the Google Developer Console, enable the Google Sheets API, and create credentials for a service account. Download the JSON file and save it as credentials.json in the project directory.

### Run the Script:

>Execute the script using the command 
``` bash 
python lead_generation.py.
```
### Email Sending:

>If you're using SMTP, ensure you have allowed "Less secure apps" access in your email settings (for Gmail). For production use, consider using a secure email sending service like SendGrid.

```
These instructions provide a clear guide for setting up and using your lead generation and email outreach automation script. Make sure to replace placeholder information with the actual details relevant to your project.
```
