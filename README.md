# Exercise 1
```
Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (deve)
$ git branch
* deve
  main

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (deve)
$ git branch -d deve
error: cannot delete branch 'deve' used by worktree at 'C:/code/git/gitadvanced'

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (deve)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (main)
$ git branch -d deve
Deleted branch deve (was 3a64c36).

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (main)
$ git branch
* main

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (main)
$ git switch -c dev
Switched to a new branch 'dev'

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (dev)
$ git branch
* dev
  main

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (dev)
$ git switch -c test
Switched to a new branch 'test'

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (test)
$ git branch
  dev
  main
* test

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (test)
$ git switch dev
Switched to branch 'dev'

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (dev)
$ git branch
* dev
  main
  test

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (dev)
$ git branch -d test
Deleted branch test (was 3a64c36).

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (dev)
$ git branch
* dev
  main

Administrator@DESKTOP-5O3LLQR MINGW64 /c/code/git/gitadvanced (dev)
$
```