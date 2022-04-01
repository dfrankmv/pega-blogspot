Here is the tracer captured during the execution of the **FinishAssignment** activity.

![image](https://user-images.githubusercontent.com/19811297/161273888-b34263d9-4d40-4cfb-8aa1-ea2a58cbaa9d.png)

## Timeline

- 101 - The Validate rule of the parent flow action 1 is executed
- 289 - The post Data Transform of the parent flow action 1 is executed
- 296 - The post Activity of the parent flow action 1 is executed
- 371 - The newAssignPage (parent assignment 1) is renamed to removeAssignPage
- 389 - The parent assignment 1 record is deleted from its database table
- 402 - The Create Case shape starts
- 474 - The IteratePage_XXX (child case) is created
- 395 - The propagate Data Transform rule is executed
- 651 - The create case Data Transform rule is executed
- 1473 - The routing (child assignment) starts
- 1491 - The child assignment starts
- 1499 - The newAssignPage (child assignment) is created
- 1619 - The newAssignPage (child assignment) is saved to its database table
- 1655 - The IteratePage_XXX (child case) is saved to its database table
- 1917 - The routing (parent assignment 2) starts
- 1935 - The parent assignment 2 starts
- 1943 - The newAssignPage (parent assignment 2) is created
- 2067 - The newAssignPage (parent assignment 2) is saved to its database table
- 2101 - The primary work object is saved
- 2692 - High-level commit
- 2783 - The Perform activity starts
- 3735 - The pre Data Transform of the parent flow action 2 is executed
- 3737 - The pre Activity of the parent flow action 2 is executed
