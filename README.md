# Monday.com Business Intelligence Agent

## Overview

This project is a **prototype AI Business Intelligence Agent** that connects to **Monday.com boards** to provide founder-level insights about deals and work orders.  

Users can ask business questions like:

- "How is our pipeline looking this quarter?"  
- "How many work orders are delayed?"  

The agent dynamically fetches data from Monday.com and provides **summaries or totals**.

---

## Project Structure
project/
├─ app.py # Main Streamlit app
├─ requirements.txt # Python dependencies

---

## Features

- **Monday.com Integration**: Reads data from Deals and Work Orders boards via API.  
- **Data Cleaning**: Handles empty or inconsistent values.  
- **Pipeline Analysis**: Calculates total deals and pipeline value.  
- **Conversational Interface**: Users type questions in a Streamlit app.  

---

## Setup Instructions

1. **Install Python 3.10+** (https://www.python.org/downloads/)  
2. **Install dependencies**:

```bash
pip install -r requirements.txt
streamlit run app.py
