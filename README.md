# Git Commands
To show logs
```shell
git log
```
<pre>git log</pre>
To show diff
<pre>git dff</pre>
To show file tracing status
<pre>git status</pre>
To show branches
<pre>git branch</pre>
To checkout some branch
<pre>git checkout <branch you wanna checkout></pre>
To create a new branch:
<pre>git checkout -b <your banch name></pre>
<pre>git branch <your branch name></pre>
To save your changes
<pre>git stage <filename></pre>
<pre>git add <filename></pre>
To commit your changes
<pre>git commit -m "your message"</pre>
To change a commit message:
<pre>git commit --amend -m "New commit message"</pre>
To push your local branch to remote
<pre>git push origin mainline</pre>
To delete a local branch:
<pre>git branch -d the_local_branch</pre>
After deleting local branch, to remove a remote branch (if you know what you are doing!)
<pre>git push origin :the_remote_branch</pre>
Undo a local commit
<pre>git reset --soft HEAD~1</pre>
Undo "git add <fileName> or git stage <fileName>"
<pre>git reset <fileName></pre>

You have 2 commits a and b, you wanna delete b in the branch
<pre>git revert <commit-id></pre>
<pre>git rebase -i HEAD~3</pre>
it will combine last 3 commits,which is a, b and -b,so a will left there

To copy one commit from branch1 to branch2
<pre>git checkout branch1</pre>
<pre>git log</pre>
copy the commit id which is the one you wanna copy
<pre>git checkout branch2</pre>
<pre>git cherry-pick <commit-id></pre>

To pull the latest change and rebase your local commit on that
<pre>git pull</pre>
<pre>git rebase - i</pre>

To create code review or do a revision
<pre>cr</pre>
<pre>cr -r<your cr number></pre>
