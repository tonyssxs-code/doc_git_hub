
# Mon repo de doc

Objectif : 

Generer un site github pages découvrir l'environnement github 

## Prérequis 
- Arborescence (locale)
    - un repertoire *github*
        - ce fichier readme.md
        
## mon code 
To run a command as administrator (user "root"), use "sudo <command>".
See "man sudo_root" for details.

idgeo@GS4:~$ sudo apt update
[sudo] password for idgeo:
Hit:1 http://archive.ubuntu.com/ubuntu noble InRelease
Get:2 http://archive.ubuntu.com/ubuntu noble-updates InRelease [126 kB]
Get:3 http://security.ubuntu.com/ubuntu noble-security InRelease [126 kB]
Get:4 http://archive.ubuntu.com/ubuntu noble-backports InRelease [126 kB]
Get:5 http://security.ubuntu.com/ubuntu noble-security/main amd64 Packages [1472 kB]
Get:6 http://archive.ubuntu.com/ubuntu noble/universe amd64 Packages [15.0 MB]
Get:7 http://security.ubuntu.com/ubuntu noble-security/main Translation-en [237 kB]
Get:8 http://security.ubuntu.com/ubuntu noble-security/main amd64 Components [21.5 kB]
Get:9 http://security.ubuntu.com/ubuntu noble-security/main amd64 c-n-f Metadata [9892 B]
Get:10 http://security.ubuntu.com/ubuntu noble-security/universe amd64 Packages [935 kB]
Get:11 http://security.ubuntu.com/ubuntu noble-security/universe Translation-en [214 kB]
Get:12 http://security.ubuntu.com/ubuntu noble-security/universe amd64 Components [74.2 kB]
Get:13 http://security.ubuntu.com/ubuntu noble-security/universe amd64 c-n-f Metadata [20.0 kB]
Get:14 http://security.ubuntu.com/ubuntu noble-security/restricted amd64 Packages [2510 kB]
Get:15 http://security.ubuntu.com/ubuntu noble-security/restricted Translation-en [581 kB]
Get:16 http://security.ubuntu.com/ubuntu noble-security/restricted amd64 Components [212 B]
Get:17 http://security.ubuntu.com/ubuntu noble-security/multiverse amd64 Packages [28.8 kB]
Get:18 http://security.ubuntu.com/ubuntu noble-security/multiverse Translation-en [6492 B]
Get:19 http://security.ubuntu.com/ubuntu noble-security/multiverse amd64 Components [212 B]
Get:20 http://security.ubuntu.com/ubuntu noble-security/multiverse amd64 c-n-f Metadata [396 B]
Get:21 http://archive.ubuntu.com/ubuntu noble/universe Translation-en [5982 kB]
Get:22 http://archive.ubuntu.com/ubuntu noble/universe amd64 Components [3871 kB]
Get:23 http://archive.ubuntu.com/ubuntu noble/universe amd64 c-n-f Metadata [301 kB]
Get:24 http://archive.ubuntu.com/ubuntu noble/multiverse amd64 Packages [269 kB]
Get:25 http://archive.ubuntu.com/ubuntu noble/multiverse Translation-en [118 kB]
Get:26 http://archive.ubuntu.com/ubuntu noble/multiverse amd64 Components [35.0 kB]
Get:27 http://archive.ubuntu.com/ubuntu noble/multiverse amd64 c-n-f Metadata [8328 B]
Get:28 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 Packages [1771 kB]
Get:29 http://archive.ubuntu.com/ubuntu noble-updates/main Translation-en [328 kB]
Get:30 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 Components [175 kB]
Get:31 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 c-n-f Metadata [16.5 kB]
Get:32 http://archive.ubuntu.com/ubuntu noble-updates/universe amd64 Packages [1556 kB]
Get:33 http://archive.ubuntu.com/ubuntu noble-updates/universe Translation-en [315 kB]
Get:34 http://archive.ubuntu.com/ubuntu noble-updates/universe amd64 Components [386 kB]
Get:35 http://archive.ubuntu.com/ubuntu noble-updates/universe amd64 c-n-f Metadata [32.6 kB]
Get:36 http://archive.ubuntu.com/ubuntu noble-updates/restricted amd64 Packages [2663 kB]
Get:37 http://archive.ubuntu.com/ubuntu noble-updates/restricted Translation-en [613 kB]
Get:38 http://archive.ubuntu.com/ubuntu noble-updates/restricted amd64 Components [212 B]
Get:39 http://archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 Packages [32.1 kB]
Get:40 http://archive.ubuntu.com/ubuntu noble-updates/multiverse Translation-en [6816 B]
Get:41 http://archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 Components [940 B]
Get:42 http://archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 c-n-f Metadata [496 B]
Get:43 http://archive.ubuntu.com/ubuntu noble-backports/main amd64 Packages [40.4 kB]
Get:44 http://archive.ubuntu.com/ubuntu noble-backports/main Translation-en [9208 B]
Get:45 http://archive.ubuntu.com/ubuntu noble-backports/main amd64 Components [7312 B]
Get:46 http://archive.ubuntu.com/ubuntu noble-backports/main amd64 c-n-f Metadata [368 B]
Get:47 http://archive.ubuntu.com/ubuntu noble-backports/universe amd64 Packages [29.5 kB]
Get:48 http://archive.ubuntu.com/ubuntu noble-backports/universe Translation-en [17.9 kB]
Get:49 http://archive.ubuntu.com/ubuntu noble-backports/universe amd64 Components [10.5 kB]
Get:50 http://archive.ubuntu.com/ubuntu noble-backports/universe amd64 c-n-f Metadata [1444 B]
Get:51 http://archive.ubuntu.com/ubuntu noble-backports/restricted amd64 Components [216 B]
Get:52 http://archive.ubuntu.com/ubuntu noble-backports/restricted amd64 c-n-f Metadata [116 B]
Get:53 http://archive.ubuntu.com/ubuntu noble-backports/multiverse amd64 Components [212 B]
Get:54 http://archive.ubuntu.com/ubuntu noble-backports/multiverse amd64 c-n-f Metadata [116 B]
Fetched 40.1 MB in 42s (961 kB/s)
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
9 packages can be upgraded. Run 'apt list --upgradable' to see them.
idgeo@GS4:~$ sudo apt upgrade -y
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Calculating upgrade... Done
The following packages will be upgraded:
  cloud-init gcc-14-base libexpat1 libgcc-s1 libgnutls30t64 libpng16-16t64 libssh-4 libstdc++6 systemd-hwe-hwdb
9 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
4 standard LTS security updates
Need to get 3020 kB of archives.
After this operation, 34.8 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 gcc-14-base amd64 14.2.0-4ubuntu2~24.04.1 [51.0 kB]
Get:2 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libstdc++6 amd64 14.2.0-4ubuntu2~24.04.1 [792 kB]
Get:3 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libgcc-s1 amd64 14.2.0-4ubuntu2~24.04.1 [78.4 kB]
Get:4 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libgnutls30t64 amd64 3.8.3-1.1ubuntu3.5 [1001 kB]
Get:5 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libexpat1 amd64 2.6.1-2ubuntu0.4 [88.2 kB]
Get:6 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 systemd-hwe-hwdb all 255.1.7 [3716 B]
Get:7 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libpng16-16t64 amd64 1.6.43-5ubuntu0.5 [188 kB]
Get:8 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libssh-4 amd64 0.10.6-2ubuntu0.3 [190 kB]
Get:9 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 cloud-init all 25.3-0ubuntu1~24.04.1 [628 kB]
Fetched 3020 kB in 20s (152 kB/s)
Preconfiguring packages ...
(Reading database ... 40805 files and directories currently installed.)
Preparing to unpack .../gcc-14-base_14.2.0-4ubuntu2~24.04.1_amd64.deb ...
Unpacking gcc-14-base:amd64 (14.2.0-4ubuntu2~24.04.1) over (14.2.0-4ubuntu2~24.04) ...
Setting up gcc-14-base:amd64 (14.2.0-4ubuntu2~24.04.1) ...
(Reading database ... 40805 files and directories currently installed.)
Preparing to unpack .../libstdc++6_14.2.0-4ubuntu2~24.04.1_amd64.deb ...
Unpacking libstdc++6:amd64 (14.2.0-4ubuntu2~24.04.1) over (14.2.0-4ubuntu2~24.04) ...
Setting up libstdc++6:amd64 (14.2.0-4ubuntu2~24.04.1) ...
(Reading database ... 40805 files and directories currently installed.)
Preparing to unpack .../libgcc-s1_14.2.0-4ubuntu2~24.04.1_amd64.deb ...
Unpacking libgcc-s1:amd64 (14.2.0-4ubuntu2~24.04.1) over (14.2.0-4ubuntu2~24.04) ...
Setting up libgcc-s1:amd64 (14.2.0-4ubuntu2~24.04.1) ...
(Reading database ... 40805 files and directories currently installed.)
Preparing to unpack .../libgnutls30t64_3.8.3-1.1ubuntu3.5_amd64.deb ...
Unpacking libgnutls30t64:amd64 (3.8.3-1.1ubuntu3.5) over (3.8.3-1.1ubuntu3.4) ...
Setting up libgnutls30t64:amd64 (3.8.3-1.1ubuntu3.5) ...
(Reading database ... 40805 files and directories currently installed.)
Preparing to unpack .../libexpat1_2.6.1-2ubuntu0.4_amd64.deb ...
Unpacking libexpat1:amd64 (2.6.1-2ubuntu0.4) over (2.6.1-2ubuntu0.3) ...
Preparing to unpack .../systemd-hwe-hwdb_255.1.7_all.deb ...
Unpacking systemd-hwe-hwdb (255.1.7) over (255.1.6) ...
Preparing to unpack .../libpng16-16t64_1.6.43-5ubuntu0.5_amd64.deb ...
Unpacking libpng16-16t64:amd64 (1.6.43-5ubuntu0.5) over (1.6.43-5ubuntu0.4) ...
Preparing to unpack .../libssh-4_0.10.6-2ubuntu0.3_amd64.deb ...
Unpacking libssh-4:amd64 (0.10.6-2ubuntu0.3) over (0.10.6-2ubuntu0.2) ...
Preparing to unpack .../cloud-init_25.3-0ubuntu1~24.04.1_all.deb ...
Unpacking cloud-init (25.3-0ubuntu1~24.04.1) over (25.2-0ubuntu1~24.04.1) ...
Setting up libexpat1:amd64 (2.6.1-2ubuntu0.4) ...
Setting up cloud-init (25.3-0ubuntu1~24.04.1) ...
Setting up libpng16-16t64:amd64 (1.6.43-5ubuntu0.5) ...
Setting up libssh-4:amd64 (0.10.6-2ubuntu0.3) ...
Setting up systemd-hwe-hwdb (255.1.7) ...
Processing triggers for rsyslog (8.2312.0-3ubuntu9.1) ...
Processing triggers for man-db (2.12.0-4build2) ...
Processing triggers for udev (255.4-1ubuntu8.12) ...
Processing triggers for libc-bin (2.39-0ubuntu8.7) ...
/sbin/ldconfig.real: /usr/lib/wsl/lib/libcuda.so.1 is not a symbolic link

idgeo@GS4:~$ sudo apt install git
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
git is already the newest version (1:2.43.0-1ubuntu7.3).
git set to manually installed.
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
idgeo@GS4:~$ git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
idgeo@GS4:~$ pwd
/home/idgeo
idgeo@GS4:~$ ls -la/
ls: invalid option -- '/'
Try 'ls --help' for more information.
idgeo@GS4:~$ ls -la /mnt/
total 8
drwxr-xr-x  6 root root 4096 Feb 19 10:10 .
drwxr-xr-x 22 root root 4096 Feb 19 10:10 ..
drwxrwxrwx  1 root root 4096 Feb 19 10:01 c
drwxrwxrwx  1 root root 4096 Feb 19 10:00 d
drwxrwxrwt  2 root root   60 Feb 19 10:10 wsl
drwxrwxrwt  7 root root  300 Feb 19 10:10 wslg
idgeo@GS4:~$ cd  /mnt/d/
idgeo@GS4:/mnt/d$ cd /Documents
-bash: cd: /Documents: No such file or directory
idgeo@GS4:/mnt/d$ cd
$RECYCLE.BIN/              System Volume Information/
idgeo@GS4:/mnt/d$ cd / Documents
-bash: cd: too many arguments
idgeo@GS4:/mnt/d$ cd /mnt/c
idgeo@GS4:/mnt/c$ cd /Documents
-bash: cd: /Documents: No such file or directory
idgeo@GS4:/mnt/c$ cd/mnt/d/Documents
-bash: cd/mnt/d/Documents: No such file or directory
idgeo@GS4:/mnt/c$ cd Users/
All Users/    Default/      Default User/ Public/       agbetey/      user/
idgeo@GS4:/mnt/c$ cd Users/agbetey/D
Desktop/   Documents/ Downloads/
idgeo@GS4:/mnt/c$ cd Users/agbetey/D
Desktop/   Documents/ Downloads/
idgeo@GS4:/mnt/c$ cd Users/agbetey/Documents/Github_doc/
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ ls
docs  readme.md
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
error: chmod on /mnt/c/Users/agbetey/Documents/Github_doc/.git/config.lock failed: Operation not permitted
fatal: could not set 'core.filemode' to 'false'
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ ls -la
total 0
drwxrwxrwx 1 root root 4096 Feb 19 10:56 .
drwxrwxrwx 1 root root 4096 Feb 19 10:49 ..
drwxrwxrwx 1 root root 4096 Feb 19 10:57 .git
drwxrwxrwx 1 root root 4096 Feb 18 12:39 docs
-rwxrwxrwx 1 root root  218 Feb 18 16:44 readme.md
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ sudo git init
[sudo] password for idgeo:
Reinitialized existing Git repository in /mnt/c/Users/agbetey/Documents/Github_doc/.git/
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ git status
fatal: detected dubious ownership in repository at '/mnt/c/Users/agbetey/Documents/Github_doc'
To add an exception for this directory, call:

        git config --global --add safe.directory /mnt/c/Users/agbetey/Documents/Github_doc
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ sudo git status
[sudo] password for idgeo:
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        docs/
        readme.md

nothing added to commit but untracked files present (use "git add" to track)
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ git add *
fatal: detected dubious ownership in repository at '/mnt/c/Users/agbetey/Documents/Github_doc'
To add an exception for this directory, call:

        git config --global --add safe.directory /mnt/c/Users/agbetey/Documents/Github_doc
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ sudo git add *
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ sudo git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   docs/index.md
        new file:   readme.md

idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ sudo git commit
Aborting commit due to empty commit message.
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ sudo git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   docs/index.md
        new file:   readme.md

idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ git commit -m "premier commit"
fatal: detected dubious ownership in repository at '/mnt/c/Users/agbetey/Documents/Github_doc'
To add an exception for this directory, call:

        git config --global --add safe.directory /mnt/c/Users/agbetey/Documents/Github_doc
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ sudo git commit -m "premier commit"
[master (root-commit) 293f5eb] premier commit
 Committer: root <root@GS4.idgeo.lan>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 12 insertions(+)
 create mode 100644 docs/index.md
 create mode 100644 readme.md
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ sudo git status
On branch master
nothing to commit, working tree clean
idgeo@GS4:/mnt/c/Users/agbetey/Documents/Github_doc$ sudo git config -- kegbetey@gmail.com
error: invalid key: kegbetey@gmail.com