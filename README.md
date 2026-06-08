This project implements an end-to-end ETL pipeline using Pentaho Spoon, integrating 5+ heterogeneous data sources (CSV, XML, JSON, Excel, ZIP). It processes and cleans 10,000+ customer and sales records through automated validation, fuzzy matching, deduplication, and error reprocessing loops. Reference data lookups, value mapping, and field-level filtering ensure standardized, production-ready output.



Multi-Source Customer Data Integration using Pentaho PDI                          

Features
Read data from TXT, Excel, ZIP, CSV, JSON, XML
Sorted Merge
Unique Rows
Value Mapper
Replace in String
Fuzzy Match
Select Values
Age Validation
Error Handling & Reprocessing
Number Range Classification



///////
Multiple Sources
      ↓
Sort Rows
      ↓
Sorted Merge
      ↓
Unique Rows
      ↓
Data Cleaning
      ↓
Fuzzy Match
      ↓
Validation
      ↓
Error Handling
      ↓
Final Output  

Ways to Handle Errors in an ETL Pipeline 

1️⃣ Discard the row — skip bad records, keep the pipeline moving
2️⃣ Separate for reprocessing — isolate errors, fix & reload later
3️⃣ Write to log — capture error details for debugging & audit
4️⃣ Store in a different file/table — keep clean data clean, bad data traceable
