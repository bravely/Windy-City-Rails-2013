# Git & Github Secrets
by [Zach Holman (@holman)](http://www.twitter.com/holman)

$750 million valuation on series a-round

## Git stuff

### Merge Strategies
`git merge master -s strategy`

`git merge master -s ours`
Long running branch that will supersede master.

`git merge master -s recursive -X patience`
better line matching for logical groups
Can also set as a global option. Makes merge smarter, but a bit slower

`man git-merge`

### Second Order Diff Trick
`git diff stash@{0}`
Good for find and replace in projects without worrying

emoji diffs

Git uses less as its pager

`git --no-pager diff`

`git stripspace`
Fixes horrible coworkers and contributors

Strips trailing whitespace… everywhere, can even pipe shit in
Run this in your editor after file saves

`git diff --check`
Fixes horrible you.

`git diff --cached`
git diff only diffs unstaged changes
Shows STAGED(but uncommitted) changes

`git merge --abort`
Aborts conflicted merge. Resets your tree.

`get merge -m`
MERGE MESSAGE FROM OUTSIDE EDITOR WOO

`git merge --no-message`
guess

`git status --ignored`
Shows the status of everything you're ignoring

`--assume-unchanged`
Temporarily ignore a file
`git update-index --assume-unchanged path_to_file`
`git update-index --assume-no-unchanged`

`git commit -m "fixes shit"` not in his mind
Good commits have:

* Short summary(title) under 50chars
* Longer description of the change that follows, around 72chars

## Github stuff
#####canonical URLs
press y on any page, creates canonical URL, won't change even if the branch does

##### curlable public keys
github.com/user.keys
Programmatically add SSH keys

##### fetching pulls
Accepting a Pull Request: Add a remote, fetch branch, merge, boring zzzz
`git fetch origin pull/id/head:name` or `git fetch origin pull/12/head:pr`, gets pull request 12, names it PR on your side

##### Live updates
Pull request pages have live updates

#### Top 5 emoji:
\#5 :clap:
\#4 :+1:
\#3 :-1:
\#2 :sparkles:
\#1 :shipit:

##### Quick quotes
use `> QUOTE HERE`
also highlight text, press r. BAM REPLY

##### Browse Stars
http://github.com/stars/username

##### Web Flow
You can do a lot without leaving the browser
Documenation, prose, quick fixes, switching away from nosql LOLOL
Frees you from git clone. They've got a lot in there, life is good 'n shit

##### issue autocomplete
type #, get a search, even full text search

##### repo redirects
Rename your repository, will redirect old URLs

#####in-repo licensing
can also add to existing license
Name new file LICENSE, will give dropdown
also works for .gitignore

##### file finder
type t, find in project. File finder. Fucking IN GITHUB FIJPEQPIFJEQPIFGJEQPIGJ
partial matches, brilliance, pfjqpjfeqpifjq

###### task lists
Use issues and pulls as todo lists
`- [ ] textext`

##### fork URLs
https://github.com/user/repo/fork
good for README links, will link to forking woot

#### Git is probably terrible
#### but it's also neato lolol
