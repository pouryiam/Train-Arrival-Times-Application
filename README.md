
# Project Title

# Train Arrival Times Application

This Python application allows users to find the next arrival time for trains at various stations. It utilizes the `pandas` library to store station names and their corresponding arrival times. The application uses `tkinter` for the graphical user interface.

### Prerequisites
- Python 3.x
- `pandas` library (install using `pip install pandas`)

### How to Use

1. **Run the Application:**
   - Make sure you have Python installed on your system.
   - Install the required `pandas` library using the command `pip install pandas`.
   - Run the Python script.

2. **Select Your Station:**
   - Upon running the application, a window will appear.
   - Select your current station from the dropdown menu.

3. **Find Next Arrival Time:**
   - Click the "Find Next Arrival Time" button to see when the next train arrives at your selected station.

### Code Explanation

- **Import Libraries:**
  ```python
  import pandas as pd
  from datetime import datetime
  import tkinter as tk
  from tkinter import ttk, messagebox


