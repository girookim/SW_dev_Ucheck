<<<<<<< HEAD
about each files
1. ucheck.sh
	the file 'ucheck.sh' is main code for ucheck system. you can sign up/login then you can modify the information of attendance.
	If you login student account, you can request about present to professor and your information in local dir is changed
	if you login professor account, you can modify every student information without request. And if there are some alarm of student's 	request, you can check then you can modify their information.

	When you sign up, two folders are made at local dir automatically, shared dir. the content of folders same each other.
		The directory like this: \home\Username\{$username}.txt
				shared dir: \home\shared\Username|{$username}.txt

How to user?
	sudo ./ucheck.sh


2. delete_user.sh
	this is the file for delete account. If you made some account using ucheck.sh for test, you can user this code for delete dummy user

How to use?
	>>> sudo ./delete_user.sh
	then you Enter the username which you want to delete. then the information of user you choose and the directory of user are deleted 	completely


3. back_up_log.sh
	this code is exsisted for back up information of users. 
	If you activate this code the folder 'back_up" is made automatically at home directory. in the folder, there are the information of 	users at 	the time you actiavate back_up_log code with time stamp.

How to use?
	sudo ./back_up_log.sh


dir
/home/username/username.txt

dir
/home/shared/group/username.txt

code_dir
/home/Ucheck/

back up file dir
/home/Backup/
=======
if you want to delete user

sudo ./delete_user.sh

then, you enter the name of user who you want to delete.(
>>>>>>> complete_version
