# RNA-Seq-Anaylsis-Example-Scanpy-Based
This is from my internship project. I used scanpy and developed configuration functinos which make anaylsis more quick. 
To avoid bugs, I recommend you to read manual. 

## `Manual`
If you see this: "`*`", that part of program CAN be configured by that command. 

If you see fully colored title "`*!* Colored Title`", that part of program MUST be configured. 

You press "`Run All`" & program will stop according to "`break_command`" you defined. You configure the related path, change parameters & run again until you satisfy from the results. 
## Quick Manual
`break_command` & move on. 
*  Define Path: `Reading Dataset` (Break Point 1)
*  Check `Normalizing` (Break Point 2) 
*  Find PCA: `PCA & Drawing Graph Of The Potantial Clusters` (Break Point 3) 
*  Find Number Of Cluster: `Configuration Of Clustering` (Break Point 4) 
*  Check Ranked Genes: `Plotting Of Ranked Gene Groups (Default Graphs)` (Break Point 5)
*  Annotate Part I: `Configuration & Plotting Part Of Annotation Part I` (Break Point 6)
*  Annotate Part II:`Configuration & Plotting Part Of Annotation Part II` (Break Point 7)
*  Inspect Reference Cell Type: `Find Resolution & Inspection Of Reference Cell Type Within Each Other` (Break Point 8) 
*  Inspect Target Cell Type:`Inspection Of Reference Cell Type With Target Cell Type` (Break Point 9) 


Program is finished when you see `Finished` You may leave your conclusions to there.  

`Must To Read:` To run this program & anlayze, you need to have `ranked_functions.py` & `gene_markers.py` files in your dataset folder. If these are missig you can use sections after `Finished` section.

For more detailed changes, function and instructions of the related functions can be read.
