:> mkdir phase-0-gps-1 

~ :> cd mkdir 
-bash: cd: mkdir: No such file or directory

~ :> ls
Applications     Library          VirtualBox VMs   octopus.zip
Desktop          Movies           beach            phase-0-gps-1
Documents        Music            devbootcamp      practice-repo
Downloads        Pictures         dotfiles         reviewandreflect
Dropbox          Public           octopus          zoo

~ :> cd phase-0-gps-1

phase-0-gps-1 :> ls -la
total 0
drwxr-xr-x   2 danielruiz  staff    68B Jun  7 20:10 .
drwxr-xr-x+ 47 danielruiz  staff   1.6K Jun  7 20:10 ..

phase-0-gps-1 :> git clone https://github.com/ruiz0493/phase-0-gps-1.git
Cloning into 'phase-0-gps-1'...
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.

phase-0-gps-1 :> ls
phase-0-gps-1

phase-0-gps-1 :> cd phase-0-gps-1/

phase-0-gps-1 :> ls
LICENSE

phase-0-gps-1 :> touch awesome_page.md

phase-0-gps-1 :> ls
LICENSE         awesome_page.md

phase-0-gps-1 :> git push origin master
Username for 'https://github.com': druiz0493@yahoo.com
Password for 'https://druiz0493@yahoo.com@github.com': 
Everything up-to-date

phase-0-gps-1 :> ls
LICENSE         awesome_page.md

phase-0-gps-1 :> mk dir add-command-log
-bash: mk: command not found

phase-0-gps-1 :> cd phase-0-gps-1
-bash: cd: phase-0-gps-1: No such file or directory

phase-0-gps-1 :> cd

~ :> cd phase-0-gps-1

phase-0-gps-1 :> ls
phase-0-gps-1

phase-0-gps-1 :> ls
add-command-log phase-0-gps-1

phase-0-gps-1 :> cd phase-0-gps-1

phase-0-gps-1 :> touch readme.md

phase-0-gps-1 :> ls
LICENSE         awesome_page.md readme.md

phase-0-gps-1 :> subl readme.md

phase-0-gps-1 :> git co -b add-command-log
Switched to a new branch 'add-command-log'
