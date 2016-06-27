HOW TO BE A TERMINAL PRO - 100 COMMANDS TO KNOW
[https://code.tutsplus.com/courses/how-to-be-a-terminal-pro](https://code.tutsplus.com/courses/how-to-be-a-terminal-pro) and [https://code.tutsplus.com/courses/advanced-command-line-techniques](https://code.tutsplus.com/courses/advanced-command-line-techniques)

In the SHELL
### hello terminal
1. echo "hello world" or with with options echo -n "hello world"
2. ctrl a and ctrl e (start and end of line)
3. Up key for previous command
4. !! for repeating previous command
5. tab and double tab
6. ~ (home directory)
7. clear
8. man echo (manual for each command)

### navigation
9. pwd (print working directory)
10. cd .. and cd folder (clear directory)
11. ls directory1 directory2 or ls -lat (list, all, time)
12. open . (open current directory)
13. open -a "Sublime Text 2" beans.txt (open beans.txt with application sublime)
14. open http:aljazeera.com/interactive (open website)
15. "file name" or file\ name (escaping spaces)
16. Drag file into terminal for path (super useful)
17. open -R file.txt (reveal)
18. killall Finder (reopen filder)

### make copy move
19. touch anewfile.txt (make a new file) or touch directory/anewfile.txt (make a new file in this directory)
20. nano afile or vim afile or vi afile
21. mkdir newdirectory
22. cp beans1.txt beans2.bak (copy a backup) or cp -r beans1 beans2 (copy recursive)
23. mv afile adirectory (rename a file) or mv afile adirectory/afilenew (move a file to a new directory)
24. mv file* adir/ (globbing)
25. cat anewfile.txt (view the contents)
26. rm santa.txt (remove it) or rm -r santa (remove and remove recursive)
27. rmdir (delete a directory) could also use rm -r (to delete a folder)
28. ln -s beans1 beans2 (soft symbolic link to point to another)
29. ln beans beans2 (hard shortcut link)

### finding files and text in files
30. find . -name "*.txt" (search current directory)
31. find . -type f (find all the files)
32. find . -iname "beans" (case insensitive file)
33. find . -size +2048 (1mb size files)
34. find . -mtime -1 (-atime -ctime) (modified, access, created)
35. find . -iname "*.txt" -or -iname "*.doc" -and mtime -1 (.doc or .txt file last modifiend one day ago)
36. find . -prune -print (only find direct children)
37. grep "hello" afile.txt (shows you which line in the code)
38. grep -ilr "hello" * (find all "hellos") (-i case insensitive -l just the files -r recursively)
39. find . -name "*.txt" -exec grep -il "Hello" {} \; (grep and find at the same time)

### finding files and text in files
40. -rw-r--r-- js staff - file, user, group, anyone else
41. drwxrwxrwx (everyone has access to read, write and execute on the directory)
42. chmod u+w (user) or chmod g+w (group) or chmod o+w (others) or chmod a+w(anyone)
43. chmod og-x afile.txt (take execution rights from othrs and from the group)
44. chmod u=rw,g=r,o=, text.txt (user can rw, group can r, others can do nothing)
45. chmod 644 text.txt (444 is equal to read for everyone)(4 read, 2 write, 1 execute)(700 user can do everything everyone else nothing)

### editing file
46. Nano poem.txt (arrow keys, control k to cut, control u to paste, control o to save file, control x to exit)
47. vim index.php (normal mode or insert mode)
48. vim NORMAL MODE (beginning gg) (shift curly brace - moves to the end of paragraph) (^ beginning of line or $ end of line) (shift colon - :set number, :syntax on, :5 (line 5), :) (shift o or shift O add a new line) (shift s - wipe out lines) (shift r - replace text) (dd - delete) (p - paste) (yy - copy) (%s/print/echo/g) (up and down arrows in :) (:w newname.php) (:wq)
49. vim INSERT MODE (you escape with esc) (u - undo ) (ctrl r - redo)
50. vim ~/.rc (type in set number, syntax on, set ignorecase)

### making tar
51. MAKING TAR FILES
	1. tar -zxvf nameoftar.tar.gz
	2. cd nameoftar
	3. ./configure
	4. make
	5. make install
	6. nameoftar --version
)

### piping-redirecting-output
52.
53.
53.