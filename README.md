# Aula-Ambiente-de-Dv-e-Opera-o

1902303@sala31911 MINGW64 ~/Desktop/Pamela
$ git status
fatal: not a git repository (or any of the parent directories): .git

1902303@sala31911 MINGW64 ~/Desktop/Pamela
$ git status
fatal: not a git repository (or any of the parent directories): .git

1902303@sala31911 MINGW64 ~/Desktop/Pamela
$ git init
Initialized empty Git repository in C:/Users/1902303/Desktop/Pamela/.git/

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        aula.txt

nothing added to commit but untracked files present (use "git add" to track)

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ git config --global user.name "Pamela Lucio"

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ git config --global user.email "pamela_lsouza@hotmail.com"

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ git remote add origin https://github.com/PamelaLucio/devops.git

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ ls
aula.txt

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        aula.txt

nothing added to commit but untracked files present (use "git add" to track)

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ git commit -m "teste"
On branch master

Initial commit

Untracked files:
        aula.txt

nothing added to commit but untracked files present

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ git add .

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ git commit -m "teste"
[master (root-commit) bbec503] teste
 1 file changed, 1 insertion(+)
 create mode 100644 aula.txt

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 219 bytes | 219.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/PamelaLucio/devops.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ git clone
fatal: You must specify a repository to clone.

usage: git clone [<options>] [--] <repo> [<dir>]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    -n, --no-checkout     don't create a checkout
    --bare                create a bare repository
    --mirror              create a mirror repository (implies bare)
    -l, --local           to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    -s, --shared          setup as shared repository
    --recursive ...       alias of --recurse-submodules
    --recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    -j, --jobs <n>        number of submodules cloned in parallel
    --template <template-directory>
                          directory from which templates will be used
    --reference <repo>    reference repository
    --reference-if-able <repo>
                          reference repository
    --dissociate          use --reference only while cloning
    -o, --origin <name>   use <name> instead of 'origin' to track upstream
    -b, --branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --upload-pack <path>
                          path to git-upload-pack on the remote
    --depth <depth>       create a shallow clone of that depth
    --shallow-since <time>
                          create a shallow clone since a specific time
    --shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --single-branch       clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --shallow-submodules  any cloned submodules will be shallow
    --separate-git-dir <gitdir>
                          separate git dir from working tree
    -c, --config <key=value>
                          set config inside the new repository
    --server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --filter <args>       object filtering
    --remote-submodules   any cloned submodules will use their remote-tracking branch


1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ git clone https://github.com/PamelaLucio/Aula-Ambiente-de-Dv-e-Opera-o.git
Cloning into 'Aula-Ambiente-de-Dv-e-Opera-o'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ ls
aula.txt  Aula-Ambiente-de-Dv-e-Opera-o

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ cd aula
aula.txt                       Aula-Ambiente-de-Dv-e-Opera-o/

1902303@sala31911 MINGW64 ~/Desktop/Pamela (master)
$ cd Aula-Ambiente-de-Dv-e-Opera-o/

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (master)
$ ls
README.md

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (master)
$ ls - la
ls: cannot access '-': No such file or directory
ls: cannot access 'la': No such file or directory

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (master)
$ ls-la
bash: ls-la: command not found

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (master)
$ ls -lrt
total 1
-rw-r--r-- 1 1902303 1049089 31 fev 28 20:15 README.md

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (master)
$ git branch
* master

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (master)
$

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (master)
$ git branch
* master

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (master)
$ git branch
* master

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (master)
$ git fetch
From https://github.com/PamelaLucio/Aula-Ambiente-de-Dv-e-Opera-o
 * [new branch]      branch2    -> origin/branch2

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (master)
$ git checkout branch2
Switched to a new branch 'branch2'
Branch 'branch2' set up to track remote branch 'branch2' from 'origin'.

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (branch2)
$ git branch
* branch2
  master

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (branch2)
$ git push
Everything up-to-date

1902303@sala31911 MINGW64 ~/Desktop/Pamela/Aula-Ambiente-de-Dv-e-Opera-o (branch2)
$
teste