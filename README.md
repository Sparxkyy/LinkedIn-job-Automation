LinkedIn Easy Apply Bot
This Python script automates the process of applying for jobs using LinkedIn's Easy Apply feature. It uses Selenium WebDriver to control the browser and interact with job listings.

🚀 Features
Automatically signs in to LinkedIn

Navigates to a job search page with preset filters

Loops through job postings

Applies to jobs with the "Easy Apply" option

Skips complex applications and those requiring additional steps

Closes modals and cleans up after each application

🧰 Requirements
Python 3.7+

Google Chrome browser

ChromeDriver

LinkedIn account

Installed Python packages:

bash
Copy
Edit
pip install selenium webdriver-manager
📁 Setup
Clone the repository or copy the script to your local machine.

Replace placeholders in the script:

python
Copy
Edit
ACCOUNT_EMAIL = "your-email@example.com"
ACCOUNT_PASSWORD = "your-password"
PHONE = "your-phone-number"
If needed, also replace:

python
Copy
Edit
YOUR CHROME DRIVER FOLDER  # with a folder path like "/Users/yourname/Downloads"
Save and run the script:

bash
Copy
Edit
python linkedin_easy_apply_bot.py
Solve the captcha manually when prompted, then press Enter to continue.

🛑 Notes
The script only works for jobs with the "Easy Apply" option.

Captcha must be completed manually.

Be respectful of LinkedIn's terms of service — automating interactions may lead to temporary or permanent suspension of your account.
