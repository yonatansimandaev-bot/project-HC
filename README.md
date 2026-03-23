# Smart Decision System

A Python + HTML system that automatically evaluates users, bans or blocks them based on defined rules, logs their activity, and keeps risk scores.  

## Features

- User evaluation based on:
  - WPM (words per minute)
  - Instant travel distance
  - Location/IP changes
  - Failed password attempts
  - Weird login times
- Logs each action with username, password hash, and last seen location
- Adjustable system standards stored in database
- Dashboard shows all users and their status
Install dependencies:
pip install -r requirements.txt
Run the system:
python app.py
Open in your browser:
http://127.0.0.1:5000/
