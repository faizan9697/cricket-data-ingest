# cricket-data-ingest

# Description: This tool helps you gather and organize cricket match data from cricsheet.org into a database for analysis.

# Usage
# Download Data
# Run this command to get the latest cricket match data:

python main.py --download

# Make sure you have Python installed on your computer.

# To check your Python version
  python --version

# Installation
# 1.Clone the Repository:
 
  git clone <repository_url>

# 2.Navigate to the Project:

  cd cricket-data-ingest

# 3.Run the Data Ingest:

   python main.py --download

# Files
# main.py: The main script for downloading and processing cricket data.
# match_results.json: Temporary file for storing match results data.
# ball_by_ball.json: Temporary file for storing ball-by-ball innings data.
# cricket_data.db: SQLite database containing processed cricket data.
# README.md: This file, providing instructions on how to use the tool.
