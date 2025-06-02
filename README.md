STEP 1:
MISSING VALUES: checked for missing values using .isnull().sum().(one were found)
STEP 2:
DUPLICATES:checked and removed duplicate rows using .drop_duplicates() (none were found)
STEP 3:
STANDARDIZED TEXT:cleaned and standardized text values in Gender and No-show columns (converted to upper case)
STEP 4:
DATE FORMATTING:converted scheduledDay and AppointmentDay columns to consistent datetime format using pd.to_datetime().
STEP 5:
RENAMED columnsNS:rename all column headers to lowercase and replaced hyphens with underscored(eg.No-show ->no_show)
STEP 6:
DATA TYPES:ensured age column is of integer type using.astype(int)
STEP 7:
EXPORTED CLEANED FILE:saved the cleaned dataset as cleaned_medical_appointments.csv

