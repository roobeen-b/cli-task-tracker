# [Task Tracker](https://roadmap.sh/projects/task-tracker)
Task tracker is a project used to track and manage your tasks.  This project consists of a simple command line interface (CLI) to track what you need to do, what you have done, and what you are currently working on.
The application runs from the command line, accepts user actions and inputs as arguments, and stores the tasks in a JSON file. The user will be able to:
- Add, Update, and Delete tasks
- Mark a task as in progress or done
- List all tasks
- List all tasks that are done
- List all tasks that are not done
- List all tasks that are in progress

# How to run the project?
  - First, clone the project repo
  - Then, run "npm install" to install the required dependencies
  - Then, run "npm build" to build the project
  - Then, you can run "node dist/index.js -h" to see all the available commands
  - For e.g., You can check all the available todos using the command "node dist/index.js -l"
  - Alternatively, you can run "npm install -g" to globally install the project.
  - After installing the project globally, you can use "task-cli" instead of "node dist/index.js" to run all the available commands. For e.g., use "task-cli -l" to list all the available todos
