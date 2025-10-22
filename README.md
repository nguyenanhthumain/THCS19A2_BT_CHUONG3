# THCS19A2_BT_CHUONG3
Administrator@Admin MINGW64 ~
$ cd Documents

Administrator@Admin MINGW64 ~/Documents
$ git clone https://github.com/lttha25174600076-svg/17_Le_Thi_Thanh_Ha.git
fatal: destination path '17_Le_Thi_Thanh_Ha' already exists and is not an empty directory.

Administrator@Admin MINGW64 ~/Documents
$ git clone https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git
Cloning into '17_DHKL19A2_Le_ThiThanh_Ha'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

Administrator@Admin MINGW64 ~/Documents
$ cd 17_DHKL19A2_Le_ThiThanh_Ha

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git config --global user.email "your_email@example.com"

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ echo "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer efficitur, eros at
lacinia suscipit, magna turpis aliquam est, sit amet aliquam quam libero id mi. Ut
vel placerat risus. Sed tempor in ex vitae sodales. Donec et tempor orci. In
pharetra viverra sagittis. Vestibulum risus ante, molestie ac eros efficitur, bibendum
tincidunt turpis. In sit amet tortor gravida, ultricies ante vitae, varius tortor.
Aliquam finibus porta nulla sed gravida. Aliquam ultricies dapibus ante eget
molestie. In hac habitasse platea dictumst. Aliquam aliquam enim at massa
pharetra, et vestibulum sapien consequat. Donec accumsan quis metus at
pellentesque. Morbi quis felis placerat, interdum justo a, aliquam risus."
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer efficitur, eros at
lacinia suscipit, magna turpis aliquam est, sit amet aliquam quam libero id mi. Ut
vel placerat risus. Sed tempor in ex vitae sodales. Donec et tempor orci. In
pharetra viverra sagittis. Vestibulum risus ante, molestie ac eros efficitur, bibendum
tincidunt turpis. In sit amet tortor gravida, ultricies ante vitae, varius tortor.
Aliquam finibus porta nulla sed gravida. Aliquam ultricies dapibus ante eget
molestie. In hac habitasse platea dictumst. Aliquam aliquam enim at massa
pharetra, et vestibulum sapien consequat. Donec accumsan quis metus at
pellentesque. Morbi quis felis placerat, interdum justo a, aliquam risus.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git add .

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git commit -m " chinh sua noi dung cua tap tin read.md "
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git push origin main
Everything up-to-date

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git checkout -b branch_1
Switched to a new branch 'branch_1'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ echo "Lorem ipsum dolor sit amet, consectetur adipiscing elit." > text_branch_1.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ git add text_branch_1.txt
warning: in the working copy of 'text_branch_1.txt', LF will be replaced by CRLF the next time Git touches it

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ git commit-m "Them file text_branch_1.txt"
git: 'commit-m' is not a git command. See 'git --help'.

The most similar command is
        commit-tree

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ git push origin branch_1
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'branch_1' on GitHub by visiting:
remote:      https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha/pull/new/branch_1
remote:
To https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git
 * [new branch]      branch_1 -> branch_1

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ git checkout main
Switched to branch 'main'
A       text_branch_1.txt
Your branch is up to date with 'origin/main'.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git checkout -b branch_2
Switched to a new branch 'branch_2'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_2)
$ echo "Praesent ullamcorper orci eu erat placerat sodales." > text_branch_2.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_2)
$ git add text_branch_2.txt
warning: in the working copy of 'text_branch_2.txt', LF will be replaced by CRLF the next time Git touches it

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_2)
$ git commit -m " them tap tin text_branch_2.txt"
[branch_2 523d1f1]  them tap tin text_branch_2.txt
 2 files changed, 2 insertions(+)
 create mode 100644 text_branch_1.txt
 create mode 100644 text_branch_2.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_2)
$ git push origin branch_2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 442 bytes | 442.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'branch_2' on GitHub by visiting:
remote:      https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha/pull/new/branch_2
remote:
To https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git
 * [new branch]      branch_2 -> branch_2

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git checkout -b branch_3
Switched to a new branch 'branch_3'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_3)
$ echo "Integer sit amet nisi aliquam, tempor libero quis, cursus erat." > text_branch_3.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_3)
$ git add text_branch_3.txt
warning: in the working copy of 'text_branch_3.txt', LF will be replaced by CRLF the next time Git touches it

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_3)
$ git commit-m " Them tap tin text_branch_3.txt"
git: 'commit-m' is not a git command. See 'git --help'.

The most similar command is
        commit-tree

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_3)
$ git push origin branch_3
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'branch_3' on GitHub by visiting:
remote:      https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha/pull/new/branch_3
remote:
To https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git
 * [new branch]      branch_3 -> branch_3

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_3)
$ git checkout main
Switched to branch 'main'
A       text_branch_3.txt
Your branch is up to date with 'origin/main'.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git checkout -b branch_4
Switched to a new branch 'branch_4'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_4)
$ echo "Cras ac mi nec nisi porta ultrices sed non ante." > text_branch_4.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_4)
$ git add text_branch_4.txt
warning: in the working copy of 'text_branch_4.txt', LF will be replaced by CRLF the next time Git touches it

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_4)
$ git commit -m " Them tap tin text_branch_4,txt"
[branch_4 479f340]  Them tap tin text_branch_4,txt
 2 files changed, 2 insertions(+)
 create mode 100644 text_branch_3.txt
 create mode 100644 text_branch_4.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_4)
$ git push origin branch_4
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 447 bytes | 447.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'branch_4' on GitHub by visiting:
remote:      https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha/pull/new/branch_4
remote:
To https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git
 * [new branch]      branch_4 -> branch_4

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_4)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git brand --delete branch_4
git: 'brand' is not a git command. See 'git --help'.

The most similar command is
        branch

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git branch -D branch_4
Deleted branch branch_4 (was 479f340).

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git branch --list
  branch_1
  branch_2
  branch_3
* main

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git branch -r
  origin/HEAD -> origin/main
  origin/branch_1
  origin/branch_2
  origin/branch_3
  origin/branch_4
  origin/main

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git pull
Already up to date.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ mkdirmain_folder
bash: mkdirmain_folder: command not found

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ mkdir main_folder

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ echo " noi dung cua main_txt_1.txt" >main_folder/main_txt_1.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ echo " noi dung cua main_txt_2.txt" >main_folder/main_txt_2.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ echo " noi dung cua main_txt_3.txt" >main_folder/main_txt_3.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git add main_folder
warning: in the working copy of 'main_folder/main_txt_1.txt', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'main_folder/main_txt_2.txt', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'main_folder/main_txt_3.txt', LF will be replaced by CRLF the next time Git touches it

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git commit -m " Them thu muc main_folder va 3 file txt"
[main bf45435]  Them thu muc main_folder va 3 file txt
 3 files changed, 3 insertions(+)
 create mode 100644 main_folder/main_txt_1.txt
 create mode 100644 main_folder/main_txt_2.txt
 create mode 100644 main_folder/main_txt_3.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 512 bytes | 512.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git
Merge made by the 'ort' strategy.
 main_folder/main_txt_1.txt | 1 +
 main_folder/main_txt_2.txt | 1 +
 main_folder/main_txt_3.txt | 1 +
 3 files changed, 3 insertions(+)
 create mode 100644 main_folder/main_txt_1.txt
 create mode 100644 main_folder/main_txt_2.txt
 create mode 100644 main_folder/main_txt_3.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_2)
$

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_2)
$ git checkout brand_2
error: pathspec 'brand_2' did not match any file(s) known to git

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_2)
$ git pull origin main
From https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha
 * branch            main       -> FETCH_HEAD
Already up to date.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_2)
$ mkdir
mkdir: missing operand
Try 'mkdir --help' for more information.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_2)
$ mkdir main_folder
mkdir: cannot create directory ‘main_folder’: File exists

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_2)
$ git checkout branch_3
Switched to branch 'branch_3'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_3)
$ git pull origin main
From https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha
 * branch            main       -> FETCH_HEAD
Updating 3f7ef64..bf45435
Fast-forward
 main_folder/main_txt_1.txt | 1 +
 main_folder/main_txt_2.txt | 1 +
 main_folder/main_txt_3.txt | 1 +
 3 files changed, 3 insertions(+)
 create mode 100644 main_folder/main_txt_1.txt
 create mode 100644 main_folder/main_txt_2.txt
 create mode 100644 main_folder/main_txt_3.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_3)
$ git push origin branch
error: src refspec branch does not match any
error: failed to push some refs to 'https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_3)
$


Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_3)
$

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_3)
$ git push origin branch_3
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git
   3f7ef64..bf45435  branch_3 -> branch_3

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_3)
$ git checkout branch_1
Switched to branch 'branch_1'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ git pull origin main
From https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha
 * branch            main       -> FETCH_HEAD
Already up to date.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ git checkout branch_1
Already on 'branch_1'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ git push origin banch_1
error: src refspec banch_1 does not match any
error: failed to push some refs to 'https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ git checkout branch_1
Already on 'branch_1'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ git checkout -b brand_5
Switched to a new branch 'brand_5'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ ls
README.md  main_folder/

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ notepad text_branch_1.txt

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git status
On branch brand_5
nothing to commit, working tree clean

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ it add text_branch_1.txt
bash: it: command not found

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git commit -m " chinh sua noi dung file text_branch_1.txt ten branch_5 "
On branch brand_5
nothing to commit, working tree clean

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git add text_branch_1.txt
fatal: pathspec 'text_branch_1.txt' did not match any files

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git commit -m " chinh sua noi dung file text_branch_1.txt tren branch_5"
On branch brand_5
nothing to commit, working tree clean

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git push origin branch_5
error: src refspec branch_5 does not match any
error: failed to push some refs to 'https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git branch -d branch_2
error: the branch 'branch_2' is not fully merged
hint: If you are sure you want to delete it, run 'git branch -D branch_2'
hint: Disable this message with "git config set advice.forceDeleteBranch false"

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git branch-D branch_3
git: 'branch-D' is not a git command. See 'git --help'.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git branch -D branch_4
error: branch 'branch_4' not found

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git push origin --delete branch_2
To https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git
 - [deleted]         branch_2

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git push origin --delete branch_3
To https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git
 - [deleted]         branch_3

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git push origin --delete branch_4
To https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha.git
 - [deleted]         branch_4

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git branch -r
  origin/HEAD -> origin/main
  origin/branch_1
  origin/main

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (brand_5)
$ git checkout branch_1
Switched to branch 'branch_1'

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ git pull origin main
From https://github.com/lttha25174600076-svg/17_DHKL19A2_Le_ThiThanh_Ha
 * branch            main       -> FETCH_HEAD
Already up to date.

Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$ git push
fatal: The current branch branch_1 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin branch_1

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Administrator@Admin MINGW64 ~/Documents/17_DHKL19A2_Le_ThiThanh_Ha (branch_1)
$
