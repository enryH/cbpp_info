## Henry's setup

### Editor
- [VSCode](https://code.visualstudio.com/) - it nicely previous MarkDown files and is relativly light-weight.
- Alternatives: [Sublime](https://www.sublimetext.com/), [Atom](https://atom.io/), [Notepad++](https://notepad-plus-plus.org/)

## git
- Command line tool for distributed version control

### Setup 
- Download [git](https://git-scm.com/) and install
- Create a [github account](https://github.com/), you can even get free professional account using [github education](https://education.github.com/)

### Creating your own branch
- 

```bash
git branch mygroupbranch # create new branch
git checkout mygroupbranch # change filesystem to new branch
```
Then you are on your own branch on your local device, which you then can synchronize with the repository

### Commiting code to a branch
Commit your code from your local branch. See using `git status` and `git diff` where you are, what changed and decide what you want to commit.

Then add file one by one to the stagging area.

```bash
git add file1 
git add file2 file3 file4 
```
Check again using `git status` if you added all you wanted. Then commit 

```bash
git commit -m "my commit message"
git push  # will promt several thing if branch does not exist on github remote server
```
