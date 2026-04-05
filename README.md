 # Excel Data Cleaning and VLOOKUP Project

## Project Overview

In this project, I worked on a production dataset in Excel and solved multiple data quality issues. The main goal was to clean the data and correctly map manager ages using VLOOKUP.

## Problem Faced

While applying VLOOKUP, some rows were showing #N/A errors even though the manager names looked the same. Also, the dataset had multiple ages for the same manager, which created confusion.

## What I Did

First, I checked the data for inconsistencies and duplicate values. Then I verified whether the names in both sheets were exactly matching.

I identified that the main issue was with the VLOOKUP range shifting when dragging the formula. To fix this, I locked the table array using absolute references.

## Formula Used

=VLOOKUP(D2,Sheet1!$A$2:$B$11,2,FALSE)

## Result

After fixing the issue, all manager ages were correctly mapped and the #N/A errors were removed.

## Skills Used

Excel, Data Cleaning, VLOOKUP, Data Validation, Debugging

## Conclusion

This project helped me understand how small mistakes like not locking the range can lead to major errors, and how to debug them effectively.
