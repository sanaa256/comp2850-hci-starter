# Evaluation Tasks — Week 9

## Task 1: Add 3 new tasks
**Scenario**: You have a quiz, a worksheet, and module feedback due soon.

**Action**:
1. Add 3 new tasks titled "2870 Quiz 5", "2870 Sheet 5", and "Module feedback".
2. Confirm that they all appear in the task list

**Success criteria**:
- Form is submitted
- New task appears immediately with HTMX or after reload with no-JS
- Message confirming successful addition shown/read by SR
- Keyboard focus remains on the 'Add New Task' input bar

**Target time**: my time = 18s (no-JS), so 36-40s
**Linked to**: Story #1,2,3,4

---

## Task 2: Edit and cancel an existing task
**Scenario**: You want to add a deadline ("by Friday") to the task for the quiz you just added, but then decide against it.

**Action**:
1. Append inline 'by Friday' to the "2870 Quiz 5" task
2. Cancel the edit
3. Confirm that the task title has stayed the same

**Success criteria**:
- Upon clicking 'Edit', task moves from view mode to edit mode
- Upon clicking 'Cancel', task moves from edit mode to view mode
- No update confirmation message

**Target time**: 
**Linked to**: Story #2,3,4

---

## Task 3: Edit and save an existing task
**Scenario**: You realised the quiz was actually for COMP2860.

**Action**:
1. Update the name of the task you just added to: "2860 Quiz 5" (only change 2870 --> 2860)
2. Confirm the task appears in the list under its updated name

**Success criteria**:
- Upon clicking 'Edit', task moves from view mode to edit mode
- Upon clicking 'Save', task moves from edit mode to view mode
- Form is submitted
- Updated task appears immediately with HTMX or after reload with no-JS
- Message confirming successful update shown/read by SR

**Target time**: 
**Linked to**: Story #1,2,3,4

---

## Task 4: Search to find an existing task and delete it
**Scenario**: You have done the module feedback and want to delete the task from the list.

**Action**:
1. Search for the task "Module feedback"
2. Delete the task
3. Confirm the task has been removed from the list

**Success criteria**:
- Relevant results immediately appear, either during search with HTMX or upon clicking 'Apply Filter' with no-JS
- Message shown/read by SR, specifying input and number of relevant items found
- Upon clicking 'Delete', task is removed. If JS-enabled, a confirmation request is first shown/read by SR.

**Target time**: my time = 13s (no-JS), so 26-30s
**Linked to**: Story #1,2,3,4

---

## Task 5: Navigate between pages
**Scenario**: 

**Action**:
1. 
2. 
3. 

**Success criteria**:
- 
- 
- 

**Target time**: 
**Linked to**: Story #


## Metrics per Task

For each task, record:
- **Time-on-task** (num seconds from start to completion)
- **Success** (1 = completed, 0 = abandoned)
- **Error count** (validation errors, wrong clicks)
- **Mode** (HTMX or no-JS)
