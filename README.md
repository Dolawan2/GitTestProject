Git commands for new projects
Empty GitHub repository

        ↓

git clone

        ↓

Create README

        ↓

git add

        ↓

git commit

        ↓

git push -u origin main, the -u is when youare making the first commit for the repo

        ↓

GitHub now has main + first commit

create new feature branch
--->
git switch -c feature/login
 -c creates the new branch, it sname is feature and swtich to to it
 because you created this branch while standing on main, it automatically has all the work that you did and pushed to gitHub

 There’s an important distinction I want to show you before we switch branches: creating a file while you’re on a branch does not automatically mean that file belongs to that branch’s committed history.