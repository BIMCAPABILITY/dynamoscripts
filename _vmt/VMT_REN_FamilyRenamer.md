# 263_VMT: FAMILY RENAMER

> #### DESCRIPTION: 
- **Checks Naming Convention in Accordance to VMT BEP for: System & Inplace Families, Materials, Linestyle, Filled Regions, Links**
- **Folder Created for Separate Renamer Script Checker per Category**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
|[2.0.0] | [CHANGELOG](/_vmt/changelog/VMT_REN_FamilyRenamer.md) |

> #### SCRIPT INFORMATION: 

| File Category| Associated Files | Dynamo Packages | Custom Packages | Revit Version | Author | Reviewed By | 
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: |
| 263_VMT |  | BumbleBee 2021.25.3| | Revit 2021.1 |Cathrine Macabuhay | |
|         |  | Clockwork 1.x 1.34.0| | |
|         |  | Crumple 2022.5.27   |
|         |  | Orchid 206.3.0.8161|
----------------------------------------------------------------
> #### SCRIPT: 

<details>
<summary>SCRIPT</summary>
<img src="/_images/vmt/VMT_Renamer.png">
</details>

------------------------------------------------------------------------------

> #### DEMO: 

> #### 01. SYSTEM FAMILY | INPLACE FAMILY | MATERIALS | FILL PATTERN | FILL REGIONS | WORKSETS

<video width="1280" height="720" controls>
 <source src="/_demo/VMT/VMTR.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
- *01: Open Worksheet from previous Naming Convention Script - Duplicate "INCORRECT" Tab - Rename as "REVISED" and Rename all Incorrect Naming Conventions*
- *02: Open Dynamo Player : Select Script Folder Location*
- *02: Assign Excel Worksheet File Paths*
- *03: Run Script*
- *04: Script Automatically Renames Elements*
- *05: Script Will Export Secondary Naming Convention Checker into the Same Worksheet under a New Tab : "REVISED 02" for Anyother Naming Still Incorrect.*


> #### 02. LINESTYLE:

<video width="1280" height="720" controls>
 <source src="/_demo/VMT/VMTRLS.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS [LINESTYLE]: 
- *01: Dynamo Player: Search for String to Rename and Assign Substitute*
- *02: Assign File Location of Previous Excel Sheet for LineStyle from Naming Convention*
- *03: Run Script*
- *04: Script Will Rename all [User Created] LineStyle Elements*
- *05: Script Will Export Secondary Naming Convention Checker into the Same Worksheet under a New Tab : "REVISED 02" for Anyother Naming Still Incorrect.*
