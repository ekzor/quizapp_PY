# quizapp_PY
A simple database-driven quiz app written in Python 2.7.

# Usage

1. Download quizapp.py and the CSV files.
2. Run quizapp.py. Make sure you have write access to the directory this is run from!
3. The app will automatically create `quizapp.sqlite` using the CSV files and seed it with fake player scores.
4. Answer questions. When a question has multiple correct answers, your response can be separated any way you please; the script doesn't differentiate between `A, B` or `ba`.

# Dependencies

All the dependencies in this project are part of the Python Standard Library and should not require separate installation. Just in case, here's a list:

- sqlite3
- csv
- textwrap
- random
- string
- os
