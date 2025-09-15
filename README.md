h2 🕌 Prayer Times Scraper (Python + Selenium)

A Python automation tool that retrieves daily Islamic prayer times for any Egyptian governorate using Selenium WebDriver. The script automates browser navigation, scrapes prayer schedules from timesprayer.com
, and saves them to a local file for easy access.

📋 Features

🌍 Dynamic Input: Enter your governorate to fetch specific prayer times

🌐 Web Automation: Navigates and scrapes data automatically using Selenium

💾 File Output: Saves prayer schedules to a UTF-8 encoded text file

🧰 Skills Demonstrated: Web scraping, automation, file handling, and user interaction

🛠 Tech Stack

Language: Python 3

Libraries: Selenium

Website Source: timesprayer.com

🚀 Installation & Usage

Clone the repository

git clone https://github.com/your-username/prayer-times-scraper.git
cd prayer-times-scraper


Install dependencies

pip install selenium


Set up WebDriver

Download and configure the appropriate WebDriver for your browser (e.g., ChromeDriver).

Run the script

python prayer_time.py


Follow the prompt

Enter your governorate.

Copy the provided file path to view your saved prayer times.

📂 Project Structure
├── prayer_time.py       # Main Python script
└── output.txt           # Prayer times file (generated after running)

📈 Future Improvements

✅ Add support for countries beyond Egypt

✅ Create a GUI version for easier use

✅ Schedule automatic daily updates

🙌 Acknowledgments

Data sourced from timesprayer.com

Powered by Python and Selenium
