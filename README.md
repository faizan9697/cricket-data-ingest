# cricket-data-ingest

# Description: This tool helps you gather and organize cricket match data from cricsheet.org into a database for analysis.

Usage
Download Data
Run this command to get the latest cricket match data:

bash
Copy code
python main.py --download
Prerequisites
Make sure you have Python installed on your computer.

bash
Copy code
# To check your Python version
python --version
Installation
Clone the Repository:

bash
Copy code
git clone <repository_url>
Navigate to the Project:

bash
Copy code
cd cricket-data-ingest
Run the Data Ingest:

bash
Copy code
python main.py --download
Files
main.py: The main script for downloading and processing cricket data.
match_results.json: Temporary file for storing match results data.
ball_by_ball.json: Temporary file for storing ball-by-ball innings data.
cricket_data.db: SQLite database containing processed cricket data.
README.md: This file, providing instructions on how to use the tool.
