# PDP_WA: FILTER WALLS <3000MM

> #### DESCRIPTION: 
- **Isolates Walls in View Below 3000mm - Retrieve Current View and All Wall Elements - Reset View Range - Reselect all Wall Elements in View.**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
|[1.0.0] | [CHANGELOG](/_pdp/changelog/PDP_WA_Below.md) |

> #### SCRIPT INFORMATION: 

| File Category| Associated Files | Dynamo Packages | Custom Packages | Revit Version | Author | Reviewed By |
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: |
| 272_PDP |  | Genius Loci 2022.7.5| | Revit 2022 | Cathrine Macabuhay | |

----------------------------------------------------------------
> #### SCRIPT: 
<img src="/_images/pdp/PDP_WA_Below.png">
----------------------------------------------------------------

> #### DEMO: 

<video width="1280" height="720" controls>
 <source src="/_demo/PDP/PDP_WA_ScriptDynamoPlayer.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
**PDP Wall Scripts are to be used in Dynamo Player by order:**

      - 01: [01] Run Walls Filter >3000mm
      - 02: [00] Run Wall Comments [Set Comment]
      - 03: [02] Run Walls Filter <3000mm
      - 04: [00] Run Wall Comments [Set Comment]
------------------------------------------------------------------
Open Dynamo Player 
- *01: Open Dynamo Player & Open PDP Scripts File Path Location*

01. Isolate Walls Above 3000mm
- *01: Open Edit Inputs [Isolate Walls Above 3000mm]*
- *02: Select View To Filter from Drop Down and Run*

02. Assign Wall Comments for Walls Above 3000mm
- *01: Open Edit Inputs [Wall Comment]*
- *02: Input Comment into Text Box*

03. Isolate Walls Below 3000mm
- *01: Open Edit Inputs [Isolate Walls Below 3000mm]*
- *02: Select View To Filter from Drop Down and Run*

04. Assign Wall Comments for Walls Below 3000mm
- *01: Open Edit Inputs [Wall Comment]*
- *02: Input Comment into Text Box*
------------------------------------------------------------------
<img src="/_images/pdp/PDPPlayer.png" 
     width="550" 
     height="400" />
