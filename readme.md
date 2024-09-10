# Linux & Git Cheat Sheet

## Command 1: `ls`

- **Description:** List files and directories.
- **Options:**
  * -l: Long format listing.
  * -a: Include hidden files hidden ones
  * -h: Human-readable file sizes.
- **Usage:**
```bash
ls
```

## Command 2: `cd`

- **Description:** Change directory.
- **Usage:**
```bash
cd /path/to/directory
```

## Command 3: `pwd`

- **Description:** Print current working directory.
- **Usage:**
```bash
pwd
```

## Command 4: `mkdir`

- **Description:** Create a new directory.
- **Usage:**
```bash
mkdir my_directory
```

## Command 5: `rm`

- **Description:** Remove files and directories.
- **Options:**
  * -r: Remove directories recursively.
  * -f: Force removal without confirmation.
- **Usage:**
```bash
rm file.txt
```

## Command 6: `cp`

- **Description:** Copy files and directories.
- **Options:**
  * -r: Copy directories recursively.
- **Usage:**
```bash
cp file.txt
```

## Command 7: `mv`

- **Description:** Move/rename files and directories.
- **Usage:**
```bash
mv file.txt directory 
```

## Command 8: `touch`

- **Description:** Create an empty file or update file timestamps.
- **Usage:**
```bash
touch file.txt
```

## Command 9: `cat`

- **Description:** View the contents of a file.
- **Usage:**
```bash
cat file.txt
```

## Command 10: `git log`

- **Description:** show the commit history for the currently active branch
- **Usage:**
```bash
git log
```

## Command 11: `git status`

- **Description:** show modified files in working directory, staged for your next commit
- **Usage:**
```bash
git status
```

## Command 12: `git add`

- **Description:** add a file as it looks now to your next commit (stage)
- **Usage:**
```bash
git add [fille]
```

## Command 13: `git reset`

- **Description:** unstage a file while retaining the changes in working directory
- **Usage:**
```bash
git reset [file]
```

## Command 14: `git diff`

- **Description:** diff of what is changed but not staged
- **Usage:**
```bash
git diff
```
