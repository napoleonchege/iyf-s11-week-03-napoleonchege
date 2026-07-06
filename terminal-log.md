## Task 5.1 - Terminal Navigation
pwd
ls
cd ~/Documents
cd ..
cd ~

## Task 5.1 - Project Structure

mkdir my-project
mkdir my-project/src
mkdir my-project/src/css
mkdir my-project/src/js
mkdir my-project/src/images
mkdir my-project/docs
mkdir my-project/tests
New-Item my-project\README.md -ItemType File

## Task 5.2 - File Operations

index.html created
Get-Content index.html
Copy-Item index.html backup.html
Move-Item backup.html docs\
Rename-Item index.html home.html
Remove-Item home.html
Copy-Item src src-backup -Recurse
mkdir archive
Move-Item src-backup archive\
mkdir empty-folder
rmdir empty-folder
Remove-Item archive -Recurse