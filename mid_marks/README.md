# Mid Marks

## Project Overview
The **Mid Marks** project analyzes mid-term exam scores of students from different sections. This dataset helps in evaluating student performance across various subjects and identifying trends in academic achievement.

## Dataset Description
The dataset represents **mid-term exam marks** of students from different sections. It contains **718 records** with student marks across various subjects.

### Dataset Overview:
- **Total Records:** 718
- **Total Columns:** 8

### Key Attributes and Their Descriptions:
- **S.NO** – Serial number of the student (some values appear to be missing at the end).
- **SECTION** – The section (group) to which the student belongs (e.g., ALPHA, ZETA).
- **DV** – Marks obtained in **Digital VLSI**.
- **M-II** – Marks obtained in **Mathematics-II**.
- **PP** – Marks obtained in **Physics Practical**.
- **BEEE** – Marks obtained in **Basic Electrical & Electronics Engineering**.
- **FL** – Marks obtained in **Foreign Language**.
- **FIMS** – Marks obtained in **Fundamentals of Information & Management Science**.

### Observations:
- Some **S.NO** values are missing towards the end, meaning student IDs might not be recorded properly for all rows.
- The dataset includes students from multiple sections, allowing for **section-wise performance analysis**.
- Marks vary across subjects, indicating **different difficulty levels** or student performance trends.
- Some students have **very low scores** (e.g., **M-II = 0** for some students), which might indicate **absent students** or poor performance in certain subjects.

## Usage
This dataset can be used for:
- Analyzing **student performance trends** across different subjects and sections.
- Conducting **statistical analysis** on student scores.
- Identifying **students at risk** based on low scores.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/mid_marks.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```sh
   python main.py
   ```
