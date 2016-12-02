# git tools

## `prune-old-branches`

List or remove old integrated branches locally and on origin.

**Bug**: It might remove the branch you are standing on which is a bad idea.

## `change-author`

Extended version of the author change
[parameterizaton](https://help.github.com/articles/changing-author-info/)
for `git filter-branch` from github. This one requires the old email
address as a parameter, and the new name/email are mine, and can be set
as parameters `name="Your name"` and `email=youraddr@example.com`.

**Bug**: Not tested.
