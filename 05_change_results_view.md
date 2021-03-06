# Change results table in the repo

Bob wants to create a new results data table which he wants Alice to have. He opens the Veda results view and creates, and saves the data table. He adds it to hthe repo as follows

1. Create a new git branch
```
git checkout -b dev_table_for_new_analysis
```
2. Adds and commits the change to the branch
```
git add AppData/ResultViews.json
git commit -m "Create new data table for new analysis"
```
3. Opening other tables will update AppData/ResultsViews.json. If these changes do not need to be kept, the can be committed to a temporary branch (see [03_change_model_data](https://github.com/DataScienceScotland/git_veda2_guidance/blob/main/03_change_model_data.md)) or stashed (see [04_change_run_manager](https://github.com/DataScienceScotland/git_veda2_guidance/blob/main/04_change_run_manager.md)).
 
4. When the changes are ready to be shared, he pushes the branch to the remote and creates a pull request as described in [03_change_model_data](https://github.com/DataScienceScotland/git_veda2_guidance/blob/main/03_change_model_data.md).
