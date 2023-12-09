Fun Activity: Importing any type of Data into Supabase and retriving query params on Postman using that data.

Do this yourself

Step 1: download the CSV file I have made and provided for you in my repository above 

Step 2: Log on to Supabase & create a new project 

Step 3: On the left menu select table editor

Step 4: Once in table editor import CSV file
<img width="1440" alt="Screenshot 2023-12-06 at 5 10 09 PM" src="https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/c300f85c-4c67-4d9f-8742-8cbfa3e6d792">

Step 5: Create a name for the imported table and select enable Row Level Security (RLS) to restrict access and write Postgres policies 
<img width="1440" alt="Screenshot 2023-12-06 at 5 25 22 PM" src="https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/2aa9e71b-79de-4533-91fd-30c0d00e8cee">

Step 6: It should look like this once the CSV is uploaded
<img width="1440" alt="Screenshot 2023-12-06 at 5 34 01 PM" src="https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/2dd55cd5-7222-4f4a-8b69-c37dc012b9b3">

Step 7: Select the collection you are working in on SupaBase & Click on the authorization tab on the top to be directed to that section
<img width="1440" alt="Screenshot 2023-12-07 at 11 50 52 AM" src="https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/299ed248-98ad-4817-917d-c0202887a6b9">

Step 8: Select API key in the type section from the drop down options
<img width="1440" alt="Screenshot 2023-12-07 at 11 51 11 AM" src="https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/4132ec6d-f300-4f51-8202-7fe08a329f29">

Step 9: Result: Your data from SupaBase database should now be imported onto Postman and it should look like this:
<img width="1440" alt="Screenshot 2023-12-09 at 2 34 43 PM" src="https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/e7304664-37d3-4f42-bdeb-70218610c210">


Step 10:  We can now start retriving query params!  In the key box type 'select' and in the value type 'id' to get each id from the CSV file.

Result:
<img width="1440" alt="Screenshot 2023-12-07 at 11 57 17 AM" src="https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/ce983eed-32e8-44c7-b3b5-1adee6641274">

Step 11: Next in the key box type 'select' and in the value type 'spots' to get all the spots from the CSV file.

Result:
<img width="1440" alt="Screenshot 2023-12-07 at 12 01 10 PM" src="https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/73a2a28c-bc51-415d-a096-69fc0f3ef67a">

Step 12: Next we will try getting only the distance! In the key box type 'select' and in the value type 'distance' to get each distance from the CSV file.

Result:
<img width="1440" alt="Screenshot 2023-12-07 at 12 02 19 PM" src="https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/a1dc2f4e-3e75-4762-91da-916cd8e0f389">

Step 13: Awesome job if you made it this far, you're a pro at this point! For the last step in the key box type 'select' and in the value type 'delicious' you should get delicious: true or false back.

Result:
<img width="1440" alt="Screenshot 2023-12-07 at 11 59 50 AM" src="https://github.com/fbgAK/265-ach2-nerdy-task/assets/147472633/5ff844d4-b3e7-4727-adb5-d1d2a5afa820">


