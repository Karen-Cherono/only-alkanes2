> # **ASSIGNMENT**
> 
> ## **On your github account, create a github repo named "Only alkanes"**
>
> First I navigated to my github account then clicked on my profile, then repositories, then new and named it only-alkanes2 then create.
>
> ## **Clone the newly created repo to your local machine**
> 
> I used the command `git clone` the ssh link
>
>  i.e `git clone git@github.com:Karen-Cherono/only-alkanes2.git`
>
> ## **Copy the contents of alkanes folder from shell-lesson-data/exercise-data/, used in previous classes, into your "Only alkanes" repo**
>
> I navigated to the alkanes directory using the commands `cd` and `ls` once in the alkanes directory i used the command
>  `cp *` the path to the only-alkanes2 directory which i got using
> the command `pwd`. The command `cp *` copied all the files in the akanes directory to the destination directory only-alkanes2
>
>  i.e  `cd shell-lesson-data/`,  `cd exercise-data/`,`cd alkanes/`,`cp *` then  `cd only-alkanes2`, `pwd /home/karencherono/only-alkanes2`
> 
> ## **Run the following command while inside the repo for j in `ls *.pdb`; do for k in {1..100}; do cp $j $(basename -s .pdb $j)$k.pdb; done; done**
>
> I copied the command above to my terminal which listed all the files with an extention  *.pdb* then listed the files ranging from 1-100
>
> 
> ## **Find the easiest way to push only the .pdb files whose number suffix is divisible by 10**
>
> First I had to add the files divisible by ten with an extension *pdb* to the staging area. I used the command `git add *0.pdb` then `git status` to see the changes i had made.
> I then commited my changes using the command `git commit -m "commit message"`
> 
> ie `git commit -m "adding_only_files_divisible_by10"`
> I finally used the command `git push` to merge the changes from the terminal with the github repo.
>
>  # **GIT COMMIT MESSAGES BEST PRACTICES AND GUIDELINES**
>
> ![git commit messages](https://initialcommit.com/img/initialcommit/git-commit-messages-best-practices.png)
>
> [find git commit messages best practises here!](https://initialcommit.com/blog/git-commit-messages-best-practices#:~:text=commit%20message%20style.-,General%20Commit%20Message%20Guidelines,by%20a%)
