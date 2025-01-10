git stash (used when u wanto something there to be there but not commited.as of now dont want to commit it)
check the status . all the files that are not add are shown in red. stash it and it goes to bg
to bring it back git stash pop
git remote -v (list all remote repos associated with local. has push and fetch. url for pushing and getting updates)
as of now fetch isnt necessary
one pull req is one branch. if u push again the same content without doing pull req the older content gets updated
.gitignore (flie that is used to hide the selected files from getting pushed into github). inside the .gitignore file write the file name
that u want to ignore
*.log is the automation of ignoring all files enfing with .log
if u want to include any specific files with .log after mentioning ignore all log files then
git add -f file_name (forces to add)