$ cd ~/zero_day  # navigate to the zero_day directory
mkdir 0x00-vagrant  # create the 0x00-vagrant directory
cd 0x00-vagrant  # navigate to the new directory
echo "This is the README file for the 0x00-vagrant directory" > README.md  # create the README file and add some text to it
git add README.md  # stage the README file for commit
git commit -m "Add README file to 0x00-vagrant directory"  # commit the changes with a message
git push  # push the changes to GitHub

