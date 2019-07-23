# gitm

Git repository status check

Check the status of local and remote git repository of a given project.

## Install

Copy the gitm executable file into one of the directories in the PATH environment variable.

```
sudo cp src/gitm /usr/local/bin
```

Verify that the file has the correct execution rights
```
sudo chmod +x /usr/local/bin/gitm
```

## Configure

Copy the .gitmrepos file to your home directory.

Edit the file by inserting a git repo for each line with the following syntax
```
<nameoftherepowithoutspaces> <absolutepathoftherepo>
```

The name of the repo must be separated from the path of the repo by a space character.

Commented lines (#) are allowed.

Example:
```
TestRepo /home/user/TestRepo
#TestOldRepo /home/user/TestOldRepo
```
