# Git Workshop for ITx students. :rocket: 

:warning:️ Do not use `git push` for this exercise!


## Task 1: 

Add a new file with name note-1.txt and make a commit on a brand new branch. Lets call it `feat/note-1`

Lets make a new branch:

`git checkout -b feat/note-1`

Now use `git status`, `git add feat/note-1`, `git commit -m "Add first note"` to make a new commit.

Take a look at your graph with `git log --oneline --graph`

Lets merge:

1. `git checkout main`
2. `git merge feat/note-1 --no-ff` 

Take a look at your graph again with `git log --oneline --graph`

Skip git push for now.

## Task 2: 

Checkout feat/note-2, and take a look with git graph. Note that feat/note-2 branch should be behind of your main branch.

Lets rebase branch 2 before we merge it like in step 1.

1. `git rebase main`
2. `git checkout main`
3. `git merge feat/note-2 --no-ff`

Take a look at your graph again with `git log --oneline --graph`


## Task 3: 

Do the same with `feat/note-3` without looking at previous steps, make a commit with `note-3` on branch `feat/note-3`. Remember to rebase before merging to keep the graph clean!


## Task 4:

It is time to make your own git repository. This could be done to an existing project without using Git, or you can just start a new project to play it around. Head over to Github.com and try to make your own git repo!
