
# Rewriting history using --amend


## Changing the last commit:

```sh
git commit --amend
```

Combines the last commit with the staged changes.

## Modify the last commit message:

Run the command with no staged changes to update the commit message.

```sh
git commit --amend
```
or
```
git commit --amend -m "Updated commit message"
```

## Modify commit author

```sh
git commit --amend --no-edit --reset-author
```

## Adding files to last commit with updating commit message

```
git commit --ament --no-edit
```
