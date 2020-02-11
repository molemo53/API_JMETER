# API_JMETER
Use of public API for assessment purposes 

Prerequisite- User is required to have already installed JMETER and ready start up apache

Below is file required to be opened/uploaded to JMETER to run tests

Step 1 - Upload TestPlan File "Public API".

Step 2 - Upload Threadgroup File "Users" 

Step 3 - Upload Sampler HTTP request "HomePage" 

Step 4 - Upload Listners to capture results "Results in Table"

Step 5 - Upload Listners to capture results "Assertion Results"

Step 6 - Upload Listners to capture results "View Results Tree"

Step 7 - Upload Assertion Check on Response

Step 8 - Upload Assertion Check on Duration

Step 9 - Upload Asserstion Check on Size

Step 10 - Add Regular Expression Extractor if unable to upload (Name: RefValue, Expression:                    <a href="(.*?)">, Template: 
          $1$, Match: 4)
          
Or    - Upload Add Regular Expression Extractor

Step 11 - Upload HTTP request "LinKs" for correltion

Step 12 - Run.




          
