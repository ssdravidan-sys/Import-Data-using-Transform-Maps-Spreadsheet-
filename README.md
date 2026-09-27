# Import-Data-using-Transform-Maps-Spreadsheet-
This micro project focuses on importing structured data from an external spreadsheet into the ServiceNow platform using Import Sets and Transform Maps. The project simulates a real-world scenario where bulk employee data is received in Excel format and must be migrated into ServiceNow efficiently and accurately

First, I prepared a spreadsheet containing the required data with proper column headings and records.

Next, in ServiceNow, I used the Import Set functionality. I uploaded the spreadsheet file into ServiceNow and selected the appropriate import options.

After uploading the file, ServiceNow created an Import Set Table. This table temporarily stores the imported data.

Then, I created or used a Transform Map. The Transform Map is used to map the columns in the spreadsheet to the corresponding fields in the ServiceNow target table.

For example, if my spreadsheet contains fields such as Name, Department, Email, and Phone Number, I can map each of these fields to the appropriate fields in the ServiceNow table.

After mapping the fields, I executed the Transform process. ServiceNow then transferred the data from the Import Set Table into the target table.

Finally, I verified the imported records to make sure that the data was transferred correctly and without errors.

So, the overall process is:

Spreadsheet → Import Set → Import Set Table → Transform Map → Target Table → Verification.
