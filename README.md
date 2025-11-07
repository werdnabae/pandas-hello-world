# Sensor Data Analysis

Simple pandas project.

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```bash
python process_sensor_data.py
```

## Files

- `sensor_data.csv`: Input data
- `process_sensor_data.py`: Analysis script
- `sensor_data_analyzed.csv`: Output results

## What It Does

1. Loads CSV data
2. Cleans missing values
3. Calculates averages by equipment
4. Flags high temperature readings (>50°C)
5. Exports results

## Requirements

- Python 3.7+
- pandas

## Sensor Data Processing

This script processes sensor data and now supports Excel files.

### Updates
- Input and output now use `.xlsx` format instead of `.csv`
- Output file: `sensor_data_analyzed.xlsx` (ignored in version control)