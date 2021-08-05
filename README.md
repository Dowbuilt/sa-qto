# sa-qto

## Objective
Create a semi-automated tool for BIM 
based projects to streamline quality takeoff & review, de-sign
revisions, and division organization. 

The output is model and quantity data that ensures fast, accurate,
and verifiable results, that are tailored to the needs 
of each job.

## How-to

There are three main components to the workflow:
* Revit Model
* SA-QTO Script
* Excel File (with input and output tabs)

###### [STEP 1] Create Folder Structure

```
PROJECT DIRECTORY
│     
└───IN
│   │ original_revit.rvt
│   │ ...
│   
└───OUT
│   │ delivarables
│   │ ...
│ 
└───WORKING
    │ 
    └───YYYY.MM.DD_SAQTO
        │ saqto_revit-model.rvt
        │ QTO.xlsx
        │ AQTO_A Model Prep.dyn
        │ AQTO_B.dyn
        │ ...
```



## Example 
https://user-images.githubusercontent.com/46875099/127904336-89771366-7374-432a-b7ef-e98bd6e4cc3e.mp4

## Notes

* Revit ungroup all elements in Dynamo
* Start in 3d view to run script a
* Delete all worksets
