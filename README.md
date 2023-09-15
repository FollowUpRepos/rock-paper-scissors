[Demo](https://followuprepos.github.io/rock-paper-scissors/)

1. `git diff` = "difference" 
    * shows in red changed or deleted lines
    * shows in green new lines

    Try `git diff main balasim` to see all the changes
    between the two branches

2. `gmit` = [alias](https://funforks.github.io/nav-menu/) for `git add . && git commit `
   opens the COMMIT_EDITMSG file to allow a full description
3. `git log` = shows all commits + messages
4. `git commit --amend` = overwrites the commit with the chance of changing the message.  
   **DO NOT USE THIS AFTER YOU PUSH TO GitHUB. It will delete your initial commit locally, and retain it on GitHub, which will make your life difficult later.**