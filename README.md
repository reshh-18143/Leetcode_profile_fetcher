# LeetCode Profile Fetcher

LeetCode Profile Fetcher is a Python project that retrieves detailed information about LeetCode users, including their ranking, problem counts by difficulty, and badges, and generates a summary in CSV and HTML formats.

## Features

- **Fetch data for a single or multiple LeetCode users**
- **Sort users by ranking**
- **Save fetched data to a CSV file**
- **Generate an HTML page to display the data with styled tables**
 
## Prerequisites

- Python 3.x
- `requests` library
- `pandas` library
- `prettytable` library

You can install these dependencies using:
```bash
pip install requests pandas prettytable

Usage
Clone the repository:

bash
git clone https://github.com/YOUR_USERNAME/LeetCodeProfileFetcher.git
cd LeetCodeProfileFetcher
Run the script:

bash
python leetcode_profile_fetcher.py
Provide the input Excel file path: The script expects an Excel file named input.xlsx with a column named 'Username' containing the LeetCode usernames you want to query.

Output: The script will generate leetcode_data.csv and leetcode_data.html containing the fetched data.

Example
Your Excel file (input.xlsx) should look like this:

Username
user1
user2
After running the script, you'll get a CSV file and an HTML file with the following structure:

CSV File:

Username	Ranking	Easy	Medium	Hard	Total Solved	Badges
user1	1234	10	20	5	35	None
user2	5678	8	15	2	25	Badge1, Badge2
HTML File: The HTML file will display the data in a styled table format. Simply open leetcode_data.html in a web browser to view the structured data.

Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any improvements or bugs.
