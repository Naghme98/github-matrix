# github-matrix
Its a github workflow that I used Matrix in it to loop over the child repos I want to create Issue there.

## How it works
- Create a Issue with "automation", "feature" and any other lable you want (you also can use the template for your ease of use ----- *****).
- Workflow will check if "automation", "feature" both exists
- It will read the repo-name's file for the child repos
- It will make an Issue with the name of the original Issue (in this repo) there
- Will copy the created Issue's link
- Will update the main Issue's description with a task list of the created child Issues
