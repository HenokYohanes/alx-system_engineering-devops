pwd                                          - prints the absolute path name of the current working directory
ls                                           - Display the contents list of your current directory
cd ~                                         - changes the working directory to the user’s home directory
ls -l                                        - Display current directory contents in a long format
ls -al                                       - Display current directory contents, including hidden files in long format
ls -lna                                      - Display current directory contents in Long format, with user and group IDs displayed numerically and hidden files
mkdir /tmp/my first directory                - create a directory
mv /tmp/betty /tmp/my first directory        - move directory
rm /tmp/my first directory/betty             - remove file
rm -rf /tmp/my first directory               - remove directory
cd -                                         - changes the working directory to the previous one
ls -al . .. /boot                            - lists all files even ones with names beginning with a period character, which are normally hidden
file /tmp/iamafile                           - prints the type of the file named
ln -s /bin/ls __ls__                         - Create a symbolic link
cp -un *.html ../                            - Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
