git remote -v
origin	https://github.com/nyu-ossd-s18/git_team_rabbit.git (fetch)
origin	https://github.com/nyu-ossd-s18/git_team_rabbit.git (push)

git remote add myfork https://github.com/Matthew-Herman/git_team_rabbit
git remote -v
myfork	https://github.com/Matthew-Herman/git_team_rabbit (fetch)
myfork	https://github.com/Matthew-Herman/git_team_rabbit (push)
origin	https://github.com/nyu-ossd-s18/git_team_rabbit.git (fetch)
origin	https://github.com/nyu-ossd-s18/git_team_rabbit.git (push)

git remote add ashley-hu  https://github.com/ashley-hu/git_team_rabbit
git remote add ola  https://github.com/oekonomi/git_team_rabbit
git remote add kenneth  https://github.com/PhrydRhys/git_team_rabbit
git remote -v
ashley-hu	https://github.com/ashley-hu/git_team_rabbit (fetch)
ashley-hu	https://github.com/ashley-hu/git_team_rabbit (push)
kenneth	https://github.com/PhrydRhys/git_team_rabbit (fetch)
kenneth	https://github.com/PhrydRhys/git_team_rabbit (push)
myfork	https://github.com/Matthew-Herman/git_team_rabbit (fetch)
myfork	https://github.com/Matthew-Herman/git_team_rabbit (push)
ola	https://github.com/oekonomi/git_team_rabbit (fetch)
ola	https://github.com/oekonomi/git_team_rabbit (push)
origin	https://github.com/nyu-ossd-s18/git_team_rabbit.git (fetch)
origin	https://github.com/nyu-ossd-s18/git_team_rabbit.git (push)

git branch another_branch
git_team_rabbit matthewherman2$ git branch
  another_branch
* master

git checkout another_branch
M	matthew.md
Switched to branch 'another_branch'


touch file_on_another_branch.md
git add file_on_another_branch.md
git commit -m "added file_on_another_branch.md"
git branch
* another_branch
  master

git branch -a
* another_branch
  master
  remotes/origin/another_branch
  remotes/origin/master

git checkout master
git pull


