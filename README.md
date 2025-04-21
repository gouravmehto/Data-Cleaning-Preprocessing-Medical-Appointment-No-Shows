# Data-Cleaning-Preprocessing-Medical-Appointment-No-Shows
Objective: To clean and prepare a raw dataset by removing nulls, duplicates, and formatting inconsistencies using **Excel**.

## 🧹 Cleaning Steps Performed:

### 1. 🧭 Applied Filters
- Enabled Excel Filters (`Data > Filter`) to explore the dataset easily.

### 2. ⚠️ Handled Missing Values
- Checked for nulls in key fields such as PatientId, AppointmentID, ScheduledDay, Age and Gender.
- Removed rows with missing data in these critical columns.

### 3. ❌ Removed Duplicate Records
- Used `Data > Remove Duplicates` across all columns to eliminate fully duplicated rows.

### 4. 🔤 Standardized Text Values

- - **Neighbourhood**: Used =PROPER() to convert to Proper Case .
- **Gender**: Replaced "f" with "Female" and "m" with "Male"

### 5. 📅 Converted Date Formats
- Reformatted `ScheduledDay` and `AppointmentDay` columns to `DD-MM-YYYY` using:
  - `Format Cells > Custom > dd-mm-yyyy`

### 6. ✏️ Renamed Column Headers
- Cleaned all column names for consistency:
  - Replaced spaces with underscores
  - Example: ScheduledDay → Scheduled_Day, No-show → No_Show

### 7. 🔢 Checked & Fixed Data Types
- Ensured Age is numeric.
- Verified ScheduledDay and AppointmentDay are in proper **Date** format.

---

## ✅ Final Deliverables
- medical_appointments_cleaned.xlsx: The cleaned Excel file

---
