I will probably add something to this file in the future, but for now, it's serving as a placeholder
to preserve the containing folder. Git does not seem to add empty folders to the repository. It doesn't
seem to preserve empty branches either. For example:

>git init //creates master branch
>git checkout -b NewBranch //creates new branch
   {edit and save 1 or more files}
>git add .
>git commit 
>git branch
* NewBranch
>git checkout master
error: pathspec 'master' did not match any file(s) know to git //*** What happened to the master branch?