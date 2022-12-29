# GH Workflow-trigger

gh cli extention to run `workflow_dispatch` via gh cli.

1. Identify if you are in a git repository folder.
2. get the location of project folder.
3. get the `.github/workflow` folder for workflow yaml files
4. scan for `workflow_dispatch` keyword in the files.
5. Return a list of files that contains the keyword.

-- Get to this point first

6. allow to trigger the workflow using existing gh commands

### Future works

- Get the workflow ID
- Live status of workflow
- If failure get the workflow error log