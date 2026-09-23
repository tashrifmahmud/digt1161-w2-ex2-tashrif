# Essential Git CLI Commands

## `git status`

Probably the command I use the most.

It shows what is going on in the repo right now, like which files are modified, staged, or still untracked.

I usually run it before and after doing something just to make sure I know what state the repo is in.

---

## `git add`

Stages changes for the next commit.

For one specific file:

`git add README.md`

For everything changed in the current repo:

`git add .`

I like `git add .` because it is quick, but I still need to be careful because it stages everything. If I only want one file in the commit, it is better to add that file directly.

---

## `git commit`

Creates a saved snapshot of the staged changes.

Example:

`git commit -m "docs: add essential git commands guide"`

The message matters because it makes the commit history easier to understand later.

---

## `git push`

Sends my local commits to GitHub.

Example:

`git push origin main`

If I am working on another branch, I push that branch instead:

`git push origin feature/cli-docs`

---

## Small things I learned

- `git status` is basically my safety check.
- `git add .` is convenient, but I should know what I am staging first.
- `git add` does not upload anything to GitHub. It only stages changes.
- `git commit` saves the change locally.
- `git push` is what sends the commit to GitHub.
- I can use `git diff` before staging if I want to see exactly what I changed.