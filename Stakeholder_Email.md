# Data Review and Discussion Request Email with StakeHolders

**Dear [Team/Stakeholder's Name],**

I hope this message finds you well. I have recently completed an initial review of the Fetch Rewards datasets—specifically focusing on receipts, users, and brands 
data—and would like to share some findings and observations that may require our attention and further discussion.

## Background on Data Handling
The datasets were provided in zipped JSON files. Using Python, I managed to read, clean, and restructure the data into a more accessible format.
During this process, I performed several quality checks and identified a few areas of concern that I believe are crucial for us to address:

### Duplicate User Records
I observed multiple records for what appears to be the same user—having identical login and creation timestamps. 
This redundancy could impact our analysis and I am keen to understand if there might be a specific reason for these duplicates.

### Inconsistencies in Brand Codes
There are numerous receipts with brand codes that do not match any entry in our brands dataset. 
This discrepancy could pose challenges in accurately aggregating data by brands for analytical purposes.

### Brand Code Formatting
The brand codes are currently non-numeric, which could lead to complications in data linkage due to minor variations in string formatting. 
I recommend considering the standardization of these codes to numerical identifiers to enhance database integrity and query efficiency.

### Data Structure Complexity
Much of our data is embedded in dictionaries (e.g., date scanned), which necessitates additional data manipulation steps. 
While I understand there might be reasons for this format, simplifying this structure could potentially decrease processing errors and improve data handling efficiency.

### Outdated Data
Our most recent data only extends to February 2021, with no entries for 2024. This gap could significantly impact our ability to analyze recent trends and market behaviors.

### Lack of Relational Integrity
There appears to be no defined relational links using foreign keys among receipts, receipt items, and brands datasets. 
This absence of relational integrity complicates the process of joining these tables for in-depth data analysis and reporting.

I believe it would be beneficial for us to discuss these points in more detail to mutually understand the implications and necessary actions. 
Could we schedule a meeting to delve deeper into these observations and outline potential solutions?

Please let me know your available times, or feel free to add a meeting to my calendar as per your convenience.

Thank you for your attention, and I look forward to our collaborative effort to enhance our data systems.

**Best regards,**

**Apeksha Udayakumar**
