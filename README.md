Microsoft Windows [Version 10.0.26100.4652]
(c) Microsoft Corporation. All rights reserved.

C:\Users\punit>cd C:\Users\punit\OneDrive\Documents\pus\reactsite01

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   restore    Restore working tree files
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   diff       Show changes between commits, commit and working tree, etc
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   backfill   Download missing objects in a partial clone
   branch     List, create, or delete branches
   commit     Record changes to the repository
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   reset      Reset current HEAD to the specified state
   switch     Switch branches
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git init
Initialized empty Git repository in C:/Users/punit/OneDrive/Documents/pus/reactsite01/.git/

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git add .
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'package-lock.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'package.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'public/index.html', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'public/manifest.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'public/robots.txt', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/App.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/App.test.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/index.css', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/index.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/reportWebVitals.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/setupTests.js', LF will be replaced by CRLF the next time Git touches it

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git commit -m "initial commit 01"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'punit@PUS-PC.(none)')

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git config --global user.name "punith-us"

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git init
Reinitialized existing Git repository in C:/Users/punit/OneDrive/Documents/pus/reactsite01/.git/

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git add .

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git commit -m "initial commit 01"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'punit@PUS-PC.(none)')

C:\Users\punit\OneDrive\Documents\pus\reactsite01>gh auth login
? Where do you use GitHub? GitHub.com
? What is your preferred protocol for Git operations on this host? HTTPS
? Authenticate Git with your GitHub credentials? Yes
? How would you like to authenticate GitHub CLI? Login with a web browser

! First copy your one-time code: 53A8-15EC
Press Enter to open https://github.com/login/device in your browser...
✓ Authentication complete.
- gh config set -h github.com git_protocol https
✓ Configured git protocol
✓ Logged in as punith-us

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git init
Reinitialized existing Git repository in C:/Users/punit/OneDrive/Documents/pus/reactsite01/.git/

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git add .

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git commit -m "initial commit 01"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'punit@PUS-PC.(none)')

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git config --global user.name "punith-us"

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git init
Reinitialized existing Git repository in C:/Users/punit/OneDrive/Documents/pus/reactsite01/.git/

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git add .

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git commit -m "initial commit 01"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'punit@PUS-PC.(none)')

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git config --global user.email "punithus19@gmail.com"

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git commit -m "initial commit 01"
[master (root-commit) ea81263] initial commit 01
 23 files changed, 17852 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 public/favicon.ico
 create mode 100644 public/index.html
 create mode 100644 public/manifest.json
 create mode 100644 public/robots.txt
 create mode 100644 src/App.js
 create mode 100644 src/App.test.js
 create mode 100644 src/assets/icons8-image-50 (1).png
 create mode 100644 src/assets/icons8-image-50.png
 create mode 100644 src/assets/icons8-image-64 (1).png
 create mode 100644 src/assets/icons8-image-64.png
 create mode 100644 src/assets/logo.png
 create mode 100644 src/components/Hero/Hero.css
 create mode 100644 src/components/Hero/Hero.jsx
 create mode 100644 src/components/navbar/navbar.css
 create mode 100644 src/components/navbar/navbar.jsx
 create mode 100644 src/index.css
 create mode 100644 src/index.js
 create mode 100644 src/reportWebVitals.js
 create mode 100644 src/setupTests.js

C:\Users\punit\OneDrive\Documents\pus\reactsite01>gh repo create
? What would you like to do? Create a new repository on github.com from scratch
? Repository name reactsite01                                                                                                                                                                                                                   ? Repository name reactsite01
? Description project to learn react
? Visibility Public
? Would you like to add a README file? Yes
? Would you like to add a .gitignore? Yes
? Choose a .gitignore template AL
? Would you like to add a license? Yes
? Choose a license GNU Affero General Public License v3.0
? This will create "reactsite01" as a public repository on github.com. Continue? Yes
✓ Created repository punith-us/reactsite01 on github.com
  https://github.com/punith-us/reactsite01
? Clone the new repository locally? No

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git checkout -b v0.1
Switched to a new branch 'v0.1'

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git push -u origin v0.1
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git push -u main v0.1
fatal: 'main' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git remote add origin https://github.com/punith-us/reactsite01

C:\Users\punit\OneDrive\Documents\pus\reactsite01>git push -u origin v0.1
Enumerating objects: 30, done.
Counting objects: 100% (30/30), done.
Delta compression using up to 6 threads
Compressing objects: 100% (29/29), done.
Writing objects: 100% (30/30), 284.32 KiB | 11.85 MiB/s, done.
Total 30 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'v0.1' on GitHub by visiting:
remote:      https://github.com/punith-us/reactsite01/pull/new/v0.1
remote:
To https://github.com/punith-us/reactsite01
 * [new branch]      v0.1 -> v0.1
branch 'v0.1' set up to track 'origin/v0.1'.

C:\Users\punit\OneDrive\Documents\pus\reactsite01>
