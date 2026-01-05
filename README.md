# Calculator (Python-DataScience)

A desktop calculator application built using Python and Tkinter, enhanced with Data Science-friendly logging and analysis features.

This project is ideal for beginners learning desktop GUI development with Python, plus basic data tracking and analytics concepts.

📖 Key Features
🧮 Calculator Functionality

✔ Standard arithmetic operations
✔ Real-time display & input
✔ Clear (C) and equals (=) functions

🧠 Data Analytics Integration

✔ Logs every calculation performed
✔ Saves calculation history to a CSV file
✔ Generates basic statistics:

Total calculations performed

Most frequent operator used

Average result value

Top 10 results

🪟 GUI with Tkinter

✔ Modern window layout
✔ Responsive button grid
✔ Keyboard support

Clone the Repository
git clone https://github.com/dhrumilc2005-a11y/Calculator.git
cd Calculator

Create & Activate Python Virtual Environment
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

Install Requirements

Create a requirements.txt that includes:

numpy
pandas
matplotlib
seaborn
tkinter

Then install:

pip install -r requirements.txt

🧠 Application Overview
📌 Main Components
File	           Description
calc_gui.py	     Tkinter UI & calculator logic
analytics.py	   Data science functions (statistics, charts)
utils.py	       Helper functions (logging, formatting)
history.csv	     Logged calculations

Running the App

From the project directory:

python calc_gui.py
