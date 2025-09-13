# Student Performance Visualization

A Python project to visualize student performance using data from CSV files. This project reads student marks, CGPA, and percentages, and generates a comprehensive plot that shows performance trends, pass/fail status, and scaled CGPA for all students.

---

## Features

- Reads data from `all_summaries.csv`.
- Cleans and processes marks data.
- Visualizes:
  - Marks obtained (bar plot)
  - CGPA (scaled by 100, color-coded by pass/fail)
  - Percentage (line plot)
- Color-coded pass/fail visualization.
- Easy-to-read roll number-based comparison.

---

## Requirements

- Python 3.7+
- Pandas
- Matplotlib
- Seaborn

Install dependencies using:

```bash
pip install pandas matplotlib seaborn
````

---

## Usage

1. Place your `all_summaries.csv` in the same directory as the script.
2. Run the visualization script:

```bash
python visulise.py
```

3. The script will generate a combined bar and line plot showing student performance.

---

## Data Format

`all_summaries.csv` should have the following columns:

| Roll Number | MARKS OBTAINED | CGPA | RESULT | PERCENTAGE |
| ----------- | -------------- | ---- | ------ | ---------- |
| 10.csv      | 616/1700       | 1.16 | FAIL   | 36.24      |

* `MARKS OBTAINED` should be in the format `obtained/total`.
* `RESULT` must be either `PASS` or `FAIL`.

---

## Visualization

* **Marks Obtained**: Blue bars
* **CGPA (scaled x100)**: Colored bars (green for PASS, red for FAIL)
* **Percentage**: Orange line plot with markers

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Author

**Syed Hammad Hashmi**

GitHub: [hashmihammad](https://github.com/hashmihammad)

Email: [hashmihammad09@gmail.com](mailto:hashmihammad09@gmail.com) | [hammadhammad09@outlook.com](mailto:hammadhammad09@outlook.com)
