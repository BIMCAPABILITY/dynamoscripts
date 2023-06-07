# GEN_WS: ASSIGN LINKTYPE WORKSET

> #### DESCRIPTION: 
- **Assigns Links (Type) to Specified Worksets by Link Batch or Individual.**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
|[1.0.0] | [CHANGELOG](/_gen/WORKSETS/1_ASSIGN/changelog/GEN_WS_AssignLinktypeWorkset.md) |

> #### SCRIPT INFORMATION: 

| File Category | Associated Files | Dynamo Packages | Custom Packages | Revit Version | Author | Reviewed By |
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: |
| GENERAL: WORKSETS_ASSIGN |  | archi-lab.net 2023.213.1523 / 2018.0.08 |  | Revit 2021.1 | Cathrine Macabuhay |

------------------------------------------------------------
> #### **SCRIPT** 

<img src="/_images/gen/WS/1_ASSIGN/GEN_WS_AssignLinktypeWorkset.png">

------------------------------------------------------------

> #### DEMO [BATCH ASSIGN]:
<video width="1280" height="720" controls>
 <source src="/_demo/GEN/WS/GEN_WS_AssignLinktypeWorkset_Batch.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS [BATCH LINKS]: 
- *01: Open Dynamo Player*
- *02: Open "Edit Inputs"*
- *03: Select Workset to Transfer to*
- *04: All Links will be Transfered to Workset*
------------------------------------------------------------
> #### DEMO [INDIVIDUAL LINKS]:
<video width="1280" height="720" controls>
 <source src="/_demo/GEN/WS/GEN_WS_AssignLinktypeWorkset_Individual.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS [INDIVIDUAL LINKS]: 
- *01: Open Dynamo Player*
- *02: Open Script by Clicking the Pencil Icon in the Dynamo Player and Unfreeze Node by Right Clicking*
- *03: Drag Wire to "Set Element Parameter by Name" into "Elements" Input*
- *04: Freeze Batch Links First Node*
- *05: Refresh Dynamo Player*
- *06: Select Link*
- *07: Select Workset to Transfer to*
- *08: Selected Link will be Transfered to Selected Workset*
------------------------------------------------------------
#### NOTE: 
- Same Process Taken to Reconnect Batch Links : Open Script and Unfreeze BAtch Assign and Reconnect Wire to "Element" Input.
