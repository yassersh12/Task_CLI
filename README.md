https://roadmap.sh/projects/task-tracker
This file contains the Task CLI app.
In this app, I implemented the CRUD operations for a Task object stored in a JSON file.

Here are the existing methods:
addTask: Adds a new task.
listTasks: Lists all tasks in the file.
listTasksByStatus: Accepts one argument for the status, which can be todo, done, or in-progress.
updateTaskStatus: Updates the status of a task based on the given parameters (id and status).
updateTaskDescription: Updates the description of a task based on the given parameters (id and description).
deleteTask: Deletes a specific task based on its ID.


You can use this file by running:
node task-cli.js <command> [arguments...]
task-cli add "Buy groceries"
task-cli update 1 "Buy groceries and cook dinner"
task-cli delete 1
task-cli mark-in-progress 1
task-cli mark-done 1
task-cli list
task-cli list done
task-cli list todo
task-cli list in-progress

