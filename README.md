# cricket.py2
This project demonstrates basic data analysis in Python using a cricket dataset. It uses pandas for data handling and matplotlib for visualizing player runs.
import pandas as pd

# Create a cricket team DataFrame
cricket = {
    "Player": [
        "Virat Kohli",
        "Rohit Sharma",
        "Shubman Gill",
        "KL Rahul",
        "Hardik Pandya",
        "Ravindra Jadeja",
        "Ravichandran Ashwin",
        "Jasprit Bumrah",
        "Mohammed Shami",
        "Mohammed Siraj",
        "Kuldeep Yadav"
    ],
    "Role": [
        "Batsman",
        "Batsman",
        "Batsman",
        "Wicket Keeper",
        "All-rounder",
        "All-rounder",
        "All-rounder",
        "Bowler",
        "Bowler",
        "Bowler",
        "Bowler"
    ],
    "Runs": [13848, 11168, 1917, 2851, 1862, 2806, 3503, 91, 161, 94, 162],
    "Wickets": [4, 9, 0, 0, 91, 323, 537, 159, 202, 71, 173]
}

df = pd.DataFrame(cricket)

print(df)
