# SQL Murder Mystery

There’s been a **murder in SQL City**! Use your SQL skills to investigate the crime, explore evidence, and figure out who committed the crime.

This repository contains all the files needed to run the SQL Murder Mystery locally using SQLite.

## 🧪 What's Included

- `sql-murder-mystery.db` – The SQLite database that holds all the relevant tables and data for the mystery.   
- `prompt_beginner.txt` / `prompt_experienced.txt` – The mystery prompts with guidance depending on your SQL experience. 
- `reference.md` – A crash-course reference for SQL commands and concepts that you’ll likely use in this mystery.   
- (Optional) Solution table – Use this to check if you’ve correctly solved the mystery. 

## 🎯 How to Get Started

1. **Clone or download** this repository to your computer.  
2. Open `sql-murder-mystery.db` in a SQLite GUI (e.g., SQLite Studio) or use SQLite CLI.  
3. Read through the `prompt_beginner.txt` (if you're new to SQL) or `prompt_experienced.txt` (if you're more comfortable).  
4. Use the `reference.md` to refresh SQL syntax or learn vocab.  
5. Write SQL queries to explore the database, find clues, and determine who the murderer is.

## 🔍 Checking Your Solution

Once you think you've identified the murderer:

```sql
INSERT INTO solution VALUES (1, 'Name of Suspect You Found');
SELECT value FROM solution;
