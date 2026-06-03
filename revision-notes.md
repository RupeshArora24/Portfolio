# Revision Notes

Use this file to record changes, updates, and revision details for your portfolio project.

## Notes

 - 
 - In `index.html` the LinkedIn link uses `target="_blank"`; this opens the link in a new browser tab or window (browser-dependent).
 - The `target` attribute controls where the linked document opens. Common values:
	 - `_self`: default, opens in the same frame or tab.
	 - `_blank`: opens in a new tab or window.
	 - `_parent`, `_top`: for framed pages (less used today).
	 - a frame name: opens the link in the named iframe or window.
 - When using `_blank`, add `rel="noopener noreferrer"` to the link to prevent security risks (tabnabbing) and to improve privacy.

## Git Commands

- `git status`
- `git add .`
- `git commit -m "Your commit message"`
- `git push`
- `git push -u origin main`
- `git push origin main`
- `git pull`
- `git fetch origin`
- `git log --oneline -n 5`
- `git remote -v`
- `git branch -vv`
- `git diff`
- `git checkout <branch>`
- `git checkout -b <new-branch>`
- `git merge <branch>`
- `git stash`
- `git stash pop`
- `git reset --hard <commit>`
- `git restore <file>`
- `git config --global user.email "rupesh.arora303@gmail.com"` - this we use to update your current mail with the mail added (as my issue was here is the mail in the vs code github branch was different so it was not showing the changes on my github account so change the mail to you verified primary mail of the gihub account)
- `git config user.email` -  this is used to check the changes are made on which email id 