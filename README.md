# Pivate to Public repository

- Copy  Private repository Link
- Open cmd
- type git clone --bare <paste your private repository link> 
- cd enter the cloned folder 
- create a public repository on your github account
- then copy public repository link
- type git remote --mirror <paste your public repository link>
- git remote -v 
- git remote set-url origin <paste your public repository link>