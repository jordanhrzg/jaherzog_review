### Code Review Defect List
##### Reviewer: Jordan Herzog 
##### GH Repo: jaherzog_review
#
| ID # | Location (file & line number) | Problem Description | Problem - Category | Problem - Severity |
|:----:|:------------------------------|:--------------------|:------------------:|:------------------:|
|1|main/Item.java - Line 2|source code file is missing file banner comment|CG|LOW|
|2|main/Item.java - Line 2|public class is missing class banner comment|CG|LOW|
|3|main/SortDemo.java - Lines 36, 83, 91, 95|public methods are missing method banner comments|CG|LOW|
|4|main/RandomNumber.java - Lines 21-31|non-public variables should be prefixed by a leading underscore|CG|LOW|
|5|main/Item.java - Line 4|attribute is not private|CG|LOW|
|6|main/Item.java - Line 4|literal value is not declared as a constant|CG|LOW|
|7|main/SortAlgos.java Line 273|complex statement does not use explicit {}|CG|LOW|
|8|main/SortDemoData.java - Lines 84-113|switch statement is used|CS|LOW|
|9|main/SortAlgos.java - Lines 225-278|long method|CS|LOW|
|10|main/SortAlgos.java - Lines 20-36|bubbleSort method does not seem to follow bubble sort algorithm|FD|MJ|