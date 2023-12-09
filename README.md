# Fun Activity: Supabase Data Import and Query Parameter Retrieval

## Overview
This README provides a step-by-step guide for importing various data types into Supabase and retrieving query parameters using Postman.

### Prerequisites
- Download the required CSV file I have made and provided for you from the repository above.

## Try It Yourself: Getting Started

### Step 1: Download CSV File
Download the CSV file provided in the repository.

### Step 2: Log in to Supabase and Create a New Project
Log in to Supabase and create a new project to manage your data.

### Step 3: Navigate to Table Editor
On the left menu, select the "Table Editor" option.

### Step 4: Import CSV File
In the Table Editor, import the downloaded CSV file.

![Import CSV](https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/c300f85c-4c67-4d9f-8742-8cbfa3e6d792)

### Step 5: Configure Table Settings
Create a name for the imported table and select "Enable Row Level Security (RLS)" to restrict access. Write Postgres policies as needed.

![Table Settings](https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/2aa9e71b-79de-4533-91fd-30c0d00e8cee)

### Step 6: Verify CSV Upload
Confirm that the CSV data has been successfully uploaded and reflects in the Supabase table.

![CSV Upload Verification](https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/2dd55cd5-7222-4f4a-8b69-c37dc012b9b3)

### Step 7: Select Collection and Authorization
Choose the collection you are working on in SupaBase and navigate to the "Authorization" tab to configure access.

![Authorization Configuration](https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/299ed248-98ad-4817-917d-c0202887a6b9)

### Step 8: Choose API Key Type
Select "API Key" from the dropdown options in the type section.

![API Key Selection](https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/4132ec6d-f300-4f51-8202-7fe08a329f29)

### Step 9: Result - Data in Postman
Your Supabase database data should now be imported into Postman.

![Data in Postman](https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/e7304664-37d3-4f42-bdeb-70218610c210)

## Query Parameter Retrieval

### Step 10: Retrieve 'id'
- In the key box, type 'select' and in the value box, type 'id' to get each ID from the CSV file.

![Retrieve ID](https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/ce983eed-32e8-44c7-b3b5-1adee6641274)

### Step 11: Retrieve 'spots'
- In the key box, type 'select' and in the value box, type 'spots' to get all the spots from the CSV file.

![Retrieve Spots](https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/73a2a28c-bc51-415d-a096-69fc0f3ef67a)

### Step 12: Retrieve 'distance'
- In the key box, type 'select' and in the value box, type 'distance' to get each distance from the CSV file.

![Retrieve Distance](https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/a1dc2f4e-3e75-4762-91da-916cd8e0f389)

### Step 13: Retrieve 'delicious'
- In the key box, type 'select' and in the value box, type 'delicious' to get 'true' or 'false' for the 'delicious' attribute.

![Retrieve Delicious](https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/5ff844d4-b3e7-4727-adb5-d1d2a5afa820)

Congratulations if you made it this far, you're a pro at this point! You have successfully imported data into Supabase and retrieved query parameters using Postman!







