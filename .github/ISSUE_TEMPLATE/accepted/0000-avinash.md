---
name: RRFC
about: Requesting Request For Comment
title: '[RRFC] <Have spearate action type for material-datatable when select ALL>'
assignees:
labels:
---

<!--
# Before Opening Please...
- [ ] Search for an existing/duplicate RRFC which might be relevant to your RRFC
-->
## Motivation ("The Why")
In the current implementation of material-datatable , there is no different action when we select all rows together, which creates problem if I want to select only the filtered rows.

### Example
If i filter out some rows from the table, with a different action i could able to select only the filtered row of the data table

### How
#### Current Behaviour
Currently if i click on select all checkbox, all the transactions got selected irrespective of if the current state is filetered/searched or not.

#### Desired Behaviour
If a different action type can be introduced in rows selection other than the common action (rowsSelected), then it might be greatly helpful ot perform the operations.

### References
https://www.npmjs.com/package/material-datatable
