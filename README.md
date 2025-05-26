# remove-duplicates
Removing duplicates in Excel
# 🧹 Remove Duplicates in Excel

## 📋 Task Overview
This project demonstrates how to identify and remove duplicate rows from a dataset using Microsoft Excel's built-in tools. The dataset used is `marketing_campaign.csv`, which contains marketing-related customer information.

---

## 📁 Files in This Repository

| File Name                                | Description                                  |
|------------------------------------------|----------------------------------------------|
| `marketing_campaign.csv`                 | Original raw dataset                         |
| `marketing_campaign cleaned file.xlsx` | Cleaned dataset with duplicate rows removed   |
| `remove_duplicates_screenshot.png`       | Screenshot showing the remove duplicates step |
| `README.md`                              | This documentation file                      |

---

## 🛠 Tools Used
- Microsoft Excel
- Excel Table tools and Data tab
- Optional: Conditional formatting and formulas

---

## ✅ Steps to Remove Duplicates in Excel

### 1. Open the Dataset
- Launch Microsoft Excel and open `marketing_campaign.csv`.

### 2. Convert the Range to a Table (optional but recommended)
- Select the entire dataset.
- Go to **Home → Format as Table**.
- Choose a style and ensure the “My table has headers” box is checked.

### 3. Use the Remove Duplicates Feature
- Click anywhere inside the table.
- Go to **Data → Remove Duplicates**.
- In the pop-up window:
  - Select the columns based on which you want to identify duplicates (e.g., all columns or just Email, ID).
  - Click **OK**.
- Excel will show how many duplicate rows were removed and how many unique rows remain.

### 4. Save the Cleaned Dataset
- Save the file as:  
  `marketing_campaign cleaned file.xlsx`

---

## 📸 Screenshot
> (Include a screenshot here named `screenshot(87).png`, showing the Remove Duplicates dialog box in Excel.)

---

## 💡 Tips
- Use Excel’s `Conditional Formatting → Highlight Duplicate Values to spot duplicates before deleting.
- If you want to remove duplicates based on a single column (like `CustomerID`), select only that column in the Remove Duplicates window.

---


