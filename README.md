# MorayLeverageBehaviors
This repository contains the data and code, describing two genres of leverage behaviors observed in the California moray (Gymnothorax modax) - Knotting and Anchoring. 

**Data files:**
PrefilteredData --> Contains observational counts of all prey handling behaviors observed during a subset of trials

AnchoringData.csv --> Contains all data for Anchoring Behaviors 

KnottingData.csv --> Contains all date for Knotting Behaviors 

**R Code Files**
Anchoring.RMD --> Contains code for statistical analysis & graphics for Anchoring Behaviors

Knotting.RMD --> Contains code for statistical analysis & graphics for Knotting Behaviors

### Anchoring Data Column Descriptions ### 
* Below are the columns and contents of AnchoringData.csv

Eel - Individual Eel ID

Exposure - The Trial ID/Recording 

Date - Trial Date

Image -  File Name for image extracted from video footage

Observer - Data recorder ID

Eel_Total - Eel total length

Eel_Snout_Vent - Eel snout to vent length

Tube_Length - Total known length of the experimental crevice ("Tube")

Crevice_Length - Distance of tube enterance edge to the fixed prey location

Anchor_Type - Tail ("Terminal"), Body, or Both 

Body_Number - How many total body anchors were observed in a bout of anchoring

A1_Length - Length of the first anchor 

A1_Length_Prop - Length of the first anchor, scaled to eel total length 

A1_Midpoint_Tube - Distance from the crevice end (prey location) to the first anchor's midpoint along the crevice wall [NOT USED IN RESULTS]

A1_Tube_Prop - A1_Midpoint_Tube, scaled proportional to crevice [NOT USED IN RESULTS]

A1_Midpoint_Body - Distance from the crevice end (prey location) to the first anchor's midpoint along the eel's body

A1_Body_Prop - A1_Midpoint_Body, scaled proportional to eel 

Origin_to_One - Inter-anchor distance from the prey location to the midpoint of the first anchor

Origin_One_Prop - Origin_to_One, scaled proportional to eel 

[....]
[Columns repeat for each consectutive body anchor -- Anchor 2, 3, 4] 

Tail_Anchor_Point - Location along the body of the each where the Terminal Anchor was formed

Tail_Anchor_Point_Prop - Tail_Anchor_Point, scaled proportional to the eel

TrueTail - was the location of the Terminal Anchor on the true tail (Yes) or body (No)



### Knotting Data Column Descriptions ### 
* Below are the columns and contents of KnottingData.csv

Eel_Name - The moray being observed
Observer - The individual research collecting data
Trial_Date - The date of the trial
Knot_type - The knot being tied (overhand, double overhand, or figure eight)
Bout Order - Within a trial, if the eel tied more than 1 knot, we recorded if this was the first, second, third bout of knotting
Knotting_Duration - How long the eel was engaged in forming and using the knot, in seconds
