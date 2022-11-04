

Install git for Windows: https://git-scm.com/download/win

Git commands
- How to clone this project from the remote repo to the local computer
<pre>
git clone https://github.com/valerievna2212/Homework.git
</pre>
- How to add new file into repo repo
<pre>
# Add file to local repo
$ git add HelloWorld.java

# Commit file (it still will be local only but ready)
$ git commit -m "added new file" HelloWorld.java
[main 765ebd1] added new file
1 file changed, 7 insertions(+)
create mode 100644 HelloWorld.java

# Send to the remote repo
$ git push
