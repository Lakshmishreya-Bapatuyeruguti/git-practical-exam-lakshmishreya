# git-practical-exam-lakshmishreya
<br>
Create one repository for practical and provide the link of it for review.

Work on below points:

1. Pull and Merge difference

- Make example of pull request and two branch merge event.

2. Rebase

- Try to rebase feature branch with master branch 

3. Change commit message

- Commit push on commit in feature branch and then change commit message

4. cherry pick

- Pick some commits from feature branch to master branch

5. Drop commit

- Remove some commit from feature branch.
<br>
****************************Git Commmands Used To Perform Above Tasks*****************************
<br>
<br>
1. Pull and Merge difference

<br>- checkedout to main branch and merged buttonfeature branch with it using command:

-> <b>git merge buttonfeature</b>

- Made a pull request to another repository by forking and cloning the project and making some changes:

- Made changes and pushed it to forked repository using command: 

-> <b>git push origin main</b>

- went to github and made a pull request
![Screenshot from 2023-01-10 17-01-09](https://user-images.githubusercontent.com/122250979/211720895-d5499661-0b7f-4a51-a6fc-ac2115b8f9f7.png)


<br>
2. Rebase


- Tried rebasing a feature branch with main branch using commands:

-> <b>git checkout main </b>


-> <b>git rebase feature</b>



<br>3. Change commit message

- changed one of the commit message from feature branch using interactive rebase commands:

-> <b>git rebase -i HEAD~2</b>


- a default editor opens up and the word 'pick' is changed to <b>'reword'</b> before the commit hash.
- after saving and exit, now opens another window in which we can enter the new commit message.

<br>4. cherry pick

- Picked few commits from feature branch to main branch after switching to main branch using commands:

-><b>git cherry-pick [hashofcommit]</b>


<br>5.Drop commit

- derpped or removed a commit from feature branch using command

-> <b>git reabse -i HEAD~3</b>


- a default editor opens up and  word 'pick' is changed to <b>'drop' </b> before the commits hash to delete commit.
- save and exit from the default editor. check git log and you will see the commit got dropped/deleted.




