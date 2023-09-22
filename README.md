# GIT COMMANDS

## View Commit History

```
git log
```

## Initialize a local git repository

```
git init
```

## Set configuration for git repository

```
git config user.name "<username>"
git config user.email "<github-email-id>"
```

## Set configuration for git globally

```
git config -g user.name "<username>"
git config -g user.email "<github-email-id>"
```

## Check status of files

```
git status
```

## Add files to staging area

```
git add <file_name>
```

## Add all files to staging area

```
git add .
```

## Commit files to git

```
git commit -m "<commit-message>"
```

## Link remote repository to local repository

```
git remote add origin <git_repo_link>
```

## Push code to repository

For first time
```
git push -u origin <branch_name>
```

For all the other times
```
git push origin <branch_name>
```