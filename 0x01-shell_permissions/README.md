The 'su betty' command will switch the current user to the user betty.<br>
The 'who am i' command prints the effective username of the current user.<br>
The 'groups' command prints all the groups the current user is a part of.<br>
The 'sudo chown betty hello' command chnages the ownder of the file hello to the user betty.<br>
The 'touch hello' command created an empty file called hello. <br>
The 'chmod u+x hello' command gives execute permission to the owner of the file hello.<br>
The 'chmod u+x,g+x,o+r hello' command gives execute permissions to the owner and group owner, and read permissions to other users.<br>
The 'chmod +x hello' command gives execute permissions to the owner, group ownder and other users without using commas.<br>
The 'chmod u= hello & chmod g= hello & chmod & o=rwx hello' command gives the owner and group no permissions and other users all permissions over the file hello without using `, ;, &&, or ||.<br>
The 'chmod u=rwx hello & chmod g=rx hello & o=wx hello' command gives the owner all permissions, the group read & execute permissions and other users write and execute permissions over the file hello without using `, ;, && or ||.<br>
The 'chmod --reference=olleh hello' command sets the mode of the file hello the same as olleh's mode.<br>
The ' find . -type d -print0 | xargs -0 -I {} chmod ugo+x {}' command adds execute permission to all subdirectories of the current directory for the owner, group owner and other users without changing regular files. <br>
The 'mkdir -m 751 my_dir' command creates the my_dir directory with permissions 751 in the working directory.<br>
The 'chown :school hello' command changes the group owner to school for the file hello.<br>
