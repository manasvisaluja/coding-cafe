Question 1: 
pwd prints the whole path of the folder/directory you are currently working in. 

Question 2: 
ls -a shows all the hidden files inside your current folder which plain ls wasn’t able to show

Question 3: 
The first column shows the file type and file permissions. it shows file types such as normal file or directory and file permissions read(r), write(w) or execute(x).

Question 4:
It works because I am currently inside the home directory which contains the coding-cafe folder. coding-cafe/week02 is a relative path because it is interpreted starting from my current working directory rather than from the root directory /.

Question 5:
The 2 jobs done by mv above are:
1.	It was used to move the file from current directory (coding-café) to week01
2.	It renamed the file to old-readme.md

Question 6:
There are 12 folders on my path

Question 7:
Python3 lies in this for me:
/opt/anaconda3/bin/python3

Question 8:
No they aren’t same as the person beside meis using WSL, while I am on MacOS

Question 9:
The shell says pyton3: command not found. This means the shell checked every directory listed in my PATH from left to right, but could not find any program named pyton3 inside any of them.

Question 10:
Because the folder name starts with a dot (.), making it a hidden directory. Plain ls ignores hidden items.


Question 11:
The terminal prompt was updated to include (.venv) at the beginning.

Question 12:
No, it is not the same path. It changed from Anaconda Python to .venv/bin/python3. This tellsthat running activate added the virtual environment's bin folder to the very front of your PATH, forcing your shell to use isolated python inside the .venv folder

Question 13:
requests, and supporting packages like certifi, charset-normalizer, idna, urllib3

Question 14:
It points back to systems default python installation because running deactivate removed the virtual environment from your PATH.

Question 15:
l -h displays file sizes innan easy-to-read format (like kilobytes 'K', megabytes 'M', or gigabytes 'G') rather than raw bytes.

Question 16:
Ctrl + C cancelled the current command you wer typing (showing a KeyboardInterrupt) but kept the Python prompt open. Ctrl + D made it exit and return to the normal terminal prompt.