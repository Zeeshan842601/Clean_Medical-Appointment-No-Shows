# Clean_Medical-Appointment-No-Shows

1. **Removed Duplicates**

   * Deleted all duplicate rows to ensure each appointment record is unique.

2. **Handled Missing Values**

   * Verified that there are no missing values across any columns.

3. **Standardized Text Columns**

   * Cleaned `gender`, `no_show`, and other categorical fields using uppercase and `TRIM()` to remove extra spaces.

4. **Fixed Number Formatting**

   * Converted scientific notation in `patient_Id` and `appointment_id` to normal number format.
   * Marked invalid age values (`0` and `-1`) as `"Missing Age"`.

5. **Formatted Date Columns**

   * Standardized `scheduled_day` and `appointment_day` into consistent `dd-mm-yyyy` date format.

6. **Cleaned Column Headers**

   * Renamed all columns to lowercase and used underscores instead of spaces for clarity.

7. **Validated Data Types**

   * Ensured proper types: integers for `age`, text for categories, and datetime format for dates.

