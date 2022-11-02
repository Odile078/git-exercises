# GIT Exercises

This projects is used to do Git exercises.

## Bundle 1

### Exercise 1

```bash
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git init
Initialized empty Git repository in C:/Users/TheGym/Documents/TheGym/gitExercises/git-exercise-1/.git/
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git branch -m main
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git add README.md
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git commit -m "Setting up the project"
[main (root-commit) a6dbf90] Setting up the project
 1 file changed, 7 insertions(+)
 create mode 100644 README.md
On branch main
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git remote add origin https://github.com/Odile078/git-exerPS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Compressing objects: 100% (2/2), done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Odile078/git-exercises.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout -b dev
Switched to a new branch 'dev'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout -b test
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git branch
  main
* test
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout dev
Switched to branch 'dev'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push origin  dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote:      https://github.com/Odile078/git-exercises/pull/new/dev
To https://github.com/Odile078/git-exercises.git
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout test
Switched to branch 'test'
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/Odile078/git-exercises/pull/new/test
remote:
To https://github.com/Odile078/git-exercises.git
 * [new branch]      test -> test
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout dev
Switched to branch 'dev'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git branch -D test
Deleted branch test (was a6dbf90).
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push origin  --delete  test
To https://github.com/Odile078/git-exercises.git
 - [deleted]         test
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout dev
Already on 'dev'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git add .
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git commit -m "Adding Exercise 1 commands to the README file"
[main 4657c17] Adding Exercise 1 commands to the README file
 1 file changed, 53 insertions(+)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 976 bytes | 488.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Odile078/git-exercises.git
   a6dbf90..4657c17  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git add .
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git commit -m "Updating the README fil"
[main 1e51b00] Updating the README fil
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 319 bytes | 159.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Odile078/git-exercises.git
   4657c17..1e51b00  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout dev
Switched to branch 'dev'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git add .
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git commit -m "Adding commands used the the README file in dev branch"
[dev 3fc0b5c] Adding commands used the the README file in dev branch
 1 file changed, 69 insertions(+)
 PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push -u origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1.08 KiB | 552.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Odile078/git-exercises.git
   a6dbf90..3fc0b5c  dev -> dev
branch 'dev' set up to track 'origin/dev'.



```
