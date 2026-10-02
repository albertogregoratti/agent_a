# Operating guide

## mandatory files
- [workflows.md](in this project folder root) - defines general rules
- [project_specs.md](in this project folder root)- defines what we are building

## How the agent works
- read the instructions provided by task files in the workflow folder (what we want to happen in `split in tasks like task_1.md, task_2.md...)
- create python scripts actions (python scripts in `scripts/`) one action for each task: task_1.py, task_2.py...

## File structure 
- `resources/` - where resources are stored
- `workflows/` - where instructions are stored in .md files
- `scripts/` - where actions are stored in .py files
- `output/` - where outputs are stored
- `temp/` - temporary files
- `.env` - environment variables and keys/API tokens

## Development rules

### Rule 1: always read the mandatory files first
- `workflows.md` and `project_specs.md` in the root of the project

### Rule 2: use python or SQL only
### Rule 3: always ask clarifying questions before starting a complex task
### Rule 4: show your plan and steps before executing
### Rule 5: every workflow has 2 files:
- a markdown file in `workflows/`
- a python file in `scripts/`

### Rule 6: build in small pieces