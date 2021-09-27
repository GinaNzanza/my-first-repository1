# my-first-repository1
Last login: Sun Sep 26 20:58:11 on ttys000
ginanzanzakiese@Ginas-MacBook-Air ~ % git clone https://github.com/Tangawisi/my-first-repository1.git
Cloning into 'my-first-repository1'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
ginanzanzakiese@Ginas-MacBook-Air ~ % cd my-first-repository1
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % mkdir session13
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % cd session13
ginanzanzakiese@Ginas-MacBook-Air session13 % touch hello.txt
ginanzanzakiese@Ginas-MacBook-Air session13 % nano hello.txt
ginanzanzakiese@Ginas-MacBook-Air session13 % cat hello.txt
Sunday September 26 2021
ginanzanzakiese@Ginas-MacBook-Air session13 % cd ..
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	session13/

nothing added to commit but untracked files present (use "git add" to track)
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % git add session13
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % git config --global nzanzag@gmail.com
error: invalid key: nzanzag@gmail.com
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % git config --global Tangawisi.nzanzag@gmail.com
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % git congig --global Tangawisi.Gina
git: 'congig' is not a git command. See 'git --help'.

The most similar command is
	config
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % git config --global Tangawisi.Gina
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % git config --global Tangawisi.nzanzag@gmail.com <github_nzanzag@gmail.com>
zsh: parse error near `\n'
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % git commit -m "my first commit"
[main f62fb0e] my first commit
 Committer: Gina Nzanza kiese <ginanzanzakiese@Ginas-MacBook-Air.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 session13/hello.txt
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % git log
commit f62fb0e84aeaadd5921376bb01c844d3617e24e8 (HEAD -> main)
Author: Gina Nzanza kiese <ginanzanzakiese@Ginas-MacBook-Air.local>
Date:   Sun Sep 26 21:20:55 2021 -0400

    my first commit

commit 38496771c6f54eedfb1c38fab236e410e46a1c4f (origin/main, origin/HEAD)
Author: Gina Nzanza <90715685+Tangawisi@users.noreply.github.com>
Date:   Sun Sep 26 21:02:37 2021 -0400

    Initial commit
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % git remote -v
origin	https://github.com/Tangawisi/my-first-repository1.git (fetch)
origin	https://github.com/Tangawisi/my-first-repository1.git (push)
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % git push
Username for 'https://github.com': Tangawisi
Password for 'https://Tangawisi@github.com': 
remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/Tangawisi/my-first-repository1.git/'
ginanzanzakiese@Ginas-MacBook-Air my-first-repository1 % 
