# Git-exercises-GYM
For TheGym Git exercises

BUNDLE1 
======

EXERCISE 1
+++++++++
LENOVO@DESKTOP-5GQ3HIK MINGW64 ~ (main)
$ git clone https://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@github.com/gitarecy/Git-exercises-GYM.git
Cloning into 'Git-exercises-GYM'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~ (main)
$ git init
Reinitialized existing Git repository in C:/Users/LENOVO/.git/

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~ (main)
$ cd  C:/Users/LENOVO/.git/Git-exercises-GYM
bash: cd: C:/Users/LENOVO/.git/Git-exercises-GYM: No such file or directory

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~ (main)
$ ls
 0x02_emacs/
'3D Objects'/
 AppData/
'Application Data'@
 Cinnamon/
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Git-exercises-GYM/
 Gym-git-exercise/
 IntelGraphicsProfiles/
'Laptop Color Brush Coffee Cartoon Background On Wooden Table.jpeg.jpg'
 Links/
'Local Settings'@
 Music/
'My Documents'@
 NTUSER.DAT
 NTUSER.DAT{f96ade59-e6d9-11ed-ad74-a8ce9348df47}.TM.blf
 NTUSER.DAT{f96ade59-e6d9-11ed-ad74-a8ce9348df47}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{f96ade59-e6d9-11ed-ad74-a8ce9348df47}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 Office16/
 Office16.zip
 OneDrive/
 Oracle/
 Pictures/
 Postman/
 PrintHood@
 Recent@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Videos/
 alx-pre_course/
 alx-zero_day/
 battery-report.html
 cynthia/
 eclipse/
 eclipse-workspace/
 edb_languagepack.exe*
 edb_languagepack.exe-20230427220315*
 edb_languagepack_2.exe*
 edb_languagepack_3.exe*
 edb_mtk.exe*
 edb_npgsql.exe*
 edb_pem_agent.exe*
 edb_pem_server.exe*
 edb_pem_sqlprofiler_pg15.exe*
 edb_pgagent_pg14.exe*
 edb_pgagent_pg15.exe*
 edb_pgbouncer.exe*
 edb_pgjdbc.exe*
 edb_psqlodbc.exe*
 edb_psqlodbc.exe-20230427220620*
 edb_psqlodbc.exe-20230430004405*
 edb_psqlodbc.exe-20230430004414*
 edb_psqlodbc.exe-20230504001328*
 edb_psqlodbc.exe-20230504001340*
 edb_psqlodbc.exe-20230504011831*
 edb_slony_i_pg96.exe*
 edb_sqlprotect_pg96.exe*
 edb_xdb_62.exe*
 edb_xdb_7.exe*
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 pemhttpd.exe*
 postgis_2_4_pg96.exe*
 postgis_2_5_pg96.exe*
 postgis_3_2_pg14.exe*
 postgis_3_3_pg14.exe*
 postgis_3_3_pg15.exe*
 postgresql_96.exe*
 repos/
 test/

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~ (main)
$ cd .git

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/.git (GIT_DIR!)
$ ls
COMMIT_EDITMSG  HEAD    description  index  logs/     refs/
FETCH_HEAD      config  hooks/       info/  objects/

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/.git (GIT_DIR!)
$ cd ..

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~ (main)
$ cd Git-exercises-GYM/

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (main)
$ vi cynthia.txt

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (main)
$ ls
README.md  cynthia.txt

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (main)
$ git add .
warning: in the working copy of 'cynthia.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (main)
$ git commit -m 'added text file'
[main 69df7ad] added text file
 1 file changed, 1 insertion(+)
 create mode 100644 cynthia.txt

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (main)
$ git config --global user.name 'gitarecy'

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (main)
$ git config --global user.email 'gitarecynthia@gmail.com'

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 288 bytes | 144.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/gitarecy/Git-exercises-GYM.git
   5093546..69df7ad  main -> main

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (main)
$ ls
README.md  cynthia.txt

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (main)
$ git checkout -b dev
Switched to a new branch 'dev'

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (dev)
$ git checkout -b test
Switched to a new branch 'test'

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (test)
$ git checkout -b dev
fatal: a branch named 'dev' already exists

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (test)
$ git checkout  dev
Switched to branch 'dev'

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (dev)
$ git branch -d test
Deleted branch test (was 69df7ad).

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (dev)
$ git add .

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (dev)
$ git commit -m 'branching'
On branch dev
nothing to commit, working tree clean

LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (dev)
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


LENOVO@DESKTOP-5GQ3HIK MINGW64 ~/Git-exercises-GYM (dev)
$ git push --set-upstream origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/gitarecy/Git-exercises-GYM/pull/new/dev
remote:
To https://github.com/gitarecy/Git-exercises-GYM.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.

