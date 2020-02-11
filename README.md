# Git-Commands
Git commands to work with while check-in to projects

1) Create a workspace locally. For ex: I created a projects folder under C:/ and clone the respository in to that folder. See below.

RPotru@2VTGFW2 MINGW64 ~
$ cd C:\projects

RPotru@2VTGFW2 MINGW64 /c/projects
$ git clone https://github.com/rpotru/PowerCLI-Scripts.git
Cloning into 'PowerCLI-Scripts'...
remote: Enumerating objects: 10, done.
remote: Total 10 (delta 0), reused 0 (delta 0), pack-reused 10
Unpacking objects: 100% (10/10), 13.91 KiB | 153.00 KiB/s, done.

RPotru@2VTGFW2 MINGW64 /c/projects
$ ls
PowerCLI-Scripts/

2) Launch Visual Studio Code and File -> Open projects. Select the folder "PowerCLI-Scripts" to open the project.

3) Create new scripts/ Make changes as needed.

4) Add the files/changes to your local repository and stages it for commit.
   git add .

5) Commit the file that you've staged in your local repository.
   git commit -m "Adding new script for networking"
   
6) git push origin






