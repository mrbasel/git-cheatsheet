## Revert to last commit and discard all changes
`git reset --hard HEAD~1`

**Note**: HEAD~1 refers to previous commit.

### Or revert to a specfic commit:
`git reset --hard <commit id>`

## Revert to last commit and keep changes unstaged
`git reset --mixed HEAD~1`

## Revet to last commit and keep changes staged
`git reset --soft HEAD~1`

## Amending the most recent commit message
Use this to change the commit message of the latest commit
`git commit --amend -m "New commit message"
