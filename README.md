# Azure_study_Note

## Azure Data Warehouse
### How to choose between replicated, hash distributed, or round robin?
1. If it's a reference table and it's not big, you would probably want to choose replicated, so that it can be join across sharded data.
2. selection of hash distribution and round robin are to avoid hot spotting


