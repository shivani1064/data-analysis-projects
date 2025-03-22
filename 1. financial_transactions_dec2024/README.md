# State Transaction

## Project Overview
The **State Transaction** project aims to analyze financial transactions occurring across different states in India. This dataset helps in understanding transaction patterns, economic activities, and financial interactions between states, making it valuable for trend analysis, policy evaluation, and economic studies.

## Dataset Description
The **State Transaction Dataset** provides detailed records of transactions, including the originating state, destination state, transaction count, and other relevant attributes.

### Dataset Overview:
- **Total Records:** 351 (from index 0 to 350)
- **Total Columns:** 7

### Key Attributes and Their Descriptions:
- **homestatecode** – Encoded numerical representation of the originating state.
- **salestatecode** – Encoded numerical representation of the destination state.
- **homestatename** – Name of the state where the transaction originates.
- **salestatename** – Name of the state where the transaction is received.
- **month** – Represents the month of the transaction (**December 2024** in this dataset).
- **year** – Represents the year of the transaction (**2024**).
- **txn_count** – The total number of financial transactions between the two states.

### Key Insights:
- The dataset is clean and complete, with no missing values.
- It covers both small-scale and high-volume transactions, providing a broad view of financial interactions at the state level.
- It can be used for **trend analysis, policy evaluation, and economic studies** to understand transaction behaviors across different states.

## Usage
This dataset can be used for:
- Analyzing **state-wise financial transactions**.
- Studying **economic interactions** between different states.
- Identifying **trends and patterns** in financial activities.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/state_transaction.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```sh
   python main.py
   ```
