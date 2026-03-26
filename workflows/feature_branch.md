## Feature Branch Workflow

The feature branch workflow is a common Git workflow used in real projects.

### How it works
- A new branch is created for each feature
- Work is done independently from the main branch
- Changes are merged back into the main branch when complete

### Example
1. Create a branch:
   git checkout -b feature/new-feature

2. Make changes and commit:
   git add .
   git commit -m "Add new feature"

3. Merge into main:
   git checkout main
   git merge feature/new-feature

### Why use it?
- Keeps the main branch stable
- Allows parallel development
- Makes collaboration easier