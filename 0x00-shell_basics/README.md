pwd prints the absolute path name of the current working director.
ls displays the contents of your current directory.
cd ~ changes the working directory to the user's home directory without using any shell variables.
ls -l lists the current directory contents in long format.
ls -a -l displays current directory content, including hidden files, in long format.
ls -lan displays current directory content in long format, with user and group IDs displayed numerically and including the hidden files.
mkdir /tmp/myfirstdirectory/ creates a directory called myfirstdirectory under the /tmp/ directory.
mv /tmp/betty /tmp/myfirstdirectory/ moves the betty file from /tmp/ to /tmp/myfirstdirectory.
rm /tmp/myfirstdirectory/betty deletes the betty file in the /tmp/myfirstdirectory directory.
rmdir /tmp/myfirstdirectory deletes the myfirstdirectory directory under the /tmp/ direcory.
cd - changes the working directory to the previous one.
ls -la . .. /boot lists all files, including the hidden ones, in long format for the current directory, the parent of the current directory and the /boot directory.
file /tmp/iamafile prints the type of file named iamfile under the /tmp directory.
ln -s /bin/ls __ls__ creates a symbolic link names __ls__ to /bin/ls in the current working directory.
rsyn -av --ignore-existing --update "*html" ../ will copy HTML files from the current working directory to the parent directory, but will skip files that already exist in the parent directory or are older than the versions in the parent directory.
