# remove_multi_files.sh

To find a specific file type, please edit "FILE-TO-FIND" in the code. 
For example, you need to remove all files of having extension- .bak or .php or .js
Then edit the files as you need - find . -name ".bak" -exec rm -rf {} \;
Save the file and run in a terminal or ssh (in server) using the command- bash remove_multi_files.sh

Be careful that, this script will delete the selected files in one shot!!!
