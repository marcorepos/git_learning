# Configure account information:

CMD> git config --global user.name "UserName"
CMD> git config --global user.email UserName@example.com

#List current configure

CMD> git config --list

# Clone remote repos 
CMD> git clone https://xxxx

# Add file to staging area

CMD> git add filename

# Commit change

CMD> git commit -m "add comment here"

# Check non track and not commited file

CMD> git status

# Check commit log
CMD> git reflog
CMD> git log -p -2
CMD> git log --oneline


# show the delta of last commit file 
CMD> git show 

# Rollback last commit file
CMD>  git reset HEAD^
CMD>  git checkout filename

# Remove file
CMD>  git rm filename

# Add tag on release
CMD> git tag -a "v1.0.0" -m "Add comment here" HEAD
CMD> git push origin tag v1.0.0

# Delete tag
CMD> git tag -d "v1.0.0"
CMD> git push --delete origin "v1.0.0"




