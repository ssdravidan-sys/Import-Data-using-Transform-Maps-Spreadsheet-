Once the file is uploaded, ServiceNow stores the data temporarily in an Import Set Table. This table acts as a temporary storage area for the imported records.

The next important step is creating a Transform Map.

A Transform Map defines how the data from the Import Set Table should be transferred into the actual ServiceNow table. Here, we perform field mapping.

For example, the spreadsheet column “Employee Name” can be mapped to the corresponding Name field in the ServiceNow target table. Similarly, Department, Email, Employee ID, and other fields can be mapped.

After completing the mapping, we run the Transform process.

During this process, ServiceNow reads the imported records and transfers them from the Import Set Table to the target table.
