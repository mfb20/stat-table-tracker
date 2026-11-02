# Stat Table Tracker

# Project Goal
Keeping statistics organized manually can be time consuming. 
For oneself it can be annoying using google tools as well if not experienced. 
Whether it's for money, number of items or any other stat, there should be an e
asy way to keep track of it and order based on a category with a table. 

# MVP Scope
- Choose the number of numerical categories.
- Choose whether to include a name column.
- Enter category names separated by spaces.
- Add records containing numerical stats and an optional name.
- Validate input for the correct number and type of values.
- Display records in an aligned table.
- Save and load tables from a file.

Example categories:
Yards Touchdowns Interceptions

Example record with names enabled:
Faris, 350, 4, 1

# Future Plans
Potential additions after the MVP:
- Sort records by a selected numerical category.
- Calculate category totals and averages.
- Edit or delete existing records.
- Add a graphical interface.

# Tech Stack
- Java
- Scanner for terminal input
- ArrayList for storing records
- Files and Path for saving and loading data
- VS Code
- GitHub
- javac and java terminal commands

# Project Structure
- src/: Java source code
- tests/: Test code and sample data
- docs/: Eisenhower Matrix and System Diagram

# Build Milestones
1. Set up the git repository and java project with a basic welcome message.
2. Add table setup prompts for the number of numerical categories and whether to include a name column.
3. Read space separated category names and check that the number matches the users selection.
4. Validate entries to reject nonnumeric stats and incorrect numbers of values without crashing.
6. Display category headings and records in an aligned table and add a menu that lets users add records, view the table, or exit.
7. Add file saving and loading so users can keep their table between sessions.
8. Fix remaining issues and write a README with instructions and example input.

# Current Status
Planning and repository setup. Application code has not been implemented yet.
