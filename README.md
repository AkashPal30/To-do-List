
# Overview

This document outlines the testing procedures for the To-Do List component to guarantee its functionality and reliability. The To-Do List component empowers users to add, remove, and mark tasks as completed, alongside supporting task sorting and filtering, with data persistence through localStorage.

# Prerequisites

-	Node.js and npm installation.
-   The To-Do List React app configured and operational.

# Test Scenarios

#### 1.	Adding a Task Steps:
    - Launch the To-Do List application.
    - Input a new task in the designated field.
    - Click the "Add Task" button. Expected Outcome.
    - Launch the To-Do List application.
    - The newly added task should appear in the list.
    - The input field should clear after task addition.

#### 2.	Removing a Task Steps:
    - If no tasks are present, add one.
    - Click the "Remove" button beside the task to delete. Expected Outcome.
    - The selected task should be deleted from the list.

#### 3.	Marking a Task as Completed Steps:
    - If no tasks are present, add one.
    - Click on the task text to mark it as completed. Expected Outcome.
    - The task text should display a line-through to signify completion.
    - Clicking the task text again should reverse the completion status.

#### 4.	Filtering Tasks Steps:
    - Add multiple tasks, marking some as completed.
    - Utilize the filter dropdown to select "All", "Completed", and "Incomplete". Expected Outcome.
    - "All" should display all tasks.
    - "Completed" should only show completed tasks.
    - "Incomplete" should only show incomplete tasks.

#### 5.	Sorting Tasks 
    - To introduce sorting to the To-Do list, implement a sorting mechanism allowing users to sort tasks by criteria like task name, creation date, or completion status.

- Steps
1. Add multiple tasks with varying names and completion statuses
2. Use the sort dropdown to select sorting criteria.

#### 6.	Data Persistence Steps:
    - Add multiple tasks.
    - Refresh the browser. Expected Outcome:
    - Tasks should persist and remain visible after page reloads.

- Manual Testing Tips:
1. Validate task input to prevent adding empty tasks.
2. Test application behavior across various browsers and devices.
3. Address edge cases like adding tasks with identical names.

# conclusion
Follow these testing procedures to ensure the To-Do List component functions seamlessly. Document any issues discovered during testing and address them promptly.





    




