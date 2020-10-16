# CIDM2020
This related to fall semester
I received the error message when wanted to activate my venv. when I watched walk through video I changed my command to source /c/users/lg/envs/bookmarks/Scripts/activate and it worked fine. But still I can't use manage.py in a Vsc. It works in Powershell.
$ python manage.py runserver
C:\ProgramData\Miniconda3\python.exe: can't open file 'manage.py': [Errno 2] No such file or directory 
I run the script in Python and got:
>>> python manage.py runserver
  File "<stdin>", line 1
    python manage.py runserver
           ^
SyntaxError: invalid syntax
  My log in page didn't work .I checked the view file ,the login was there. I rewrote everything again this time it worked.
  NoReverseMatch at /account/login/
Reverse for 'register' not found. 'register' is not a valid view function or pattern name.
Request Method:	GET
Request URL:	http://127.0.0.1:8000/account/login/
Django Version:	3.1.1
Exception Type:	NoReverseMatch
Exception Value:	
Reverse for 'register' not found. 'register' is not a valid view function or pattern name.
Exception Location:	C:\Users\LG\AppData\Local\Programs\Python\Python38-32\lib\site-packages\django\urls\resolvers.py, line 685, in _reverse_with_prefix
Python Executable:	C:\Users\LG\AppData\Local\Programs\Python\Python38-32\python.exe
Python Version:	3.8.5
Python Path:	
['C:\\bookmarks\\bookmarks',
 'C:\\Users\\LG\\AppData\\Local\\Programs\\Python\\Python38-32\\python38.zip',
 'C:\\Users\\LG\\AppData\\Local\\Programs\\Python\\Python38-32\\DLLs',
 'C:\\Users\\LG\\AppData\\Local\\Programs\\Python\\Python38-32\\lib',
 'C:\\Users\\LG\\AppData\\Local\\Programs\\Python\\Python38-32',
 'C:\\Users\\LG\\AppData\\Roaming\\Python\\Python38\\site-packages',
 'C:\\Users\\LG\\AppData\\Local\\Programs\\Python\\Python38-32\\lib\\site-packages']
Server time:	Fri, 16 Oct 2020 17:18:56 +0000
  I received some others errors but I forgot to copy the log file but by google them and also watching walktrough videos I could fix them. Thanks Dr. Babb for preparing walkthrough vidios. They helped me.
  
