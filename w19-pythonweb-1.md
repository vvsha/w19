Работает под Python27

> cd c:\ve\w19
> c:\Python27\python -m venv myvenv
c:\Python27\python.exe: No module named venv
> c:\Python27\Scripts\virtualenv myvenv		// vv: или c:\ve\w19\myvenv
>A	 myvenv\Scripts\activate
(myvenv) Viva@VIVAN c:\ve\w19
>

PyCharm: Open w19	
File > Settings > Project: w19 > Project Interpreter > C:\ve\w19\myvenv\Script\python.exe
Open: c:\ve\w19\pythonweb\webserver.py
Run > Run > webserver>Run
+++
C:\ve\w19\myvenv\Scripts\python.exe C:/ve/w19/pythonweb/webserver.py
started httpserver...
запускаю руками:
c:\ve\w19\pythonweb\index.html
браузер:
Shouts going out.
запускаю руками:
c:\ve\w19\pythonweb\upload.html
браузер:
File to upload: Выберите файл
Press to upload the file!
нажимаю кнопку Press
браузер меняет адрес на 127.0.0.1 и печатает:
POST OK.
PyCharm:
Close ("X") > Terminate
VCS > Import Version Control > Share Project on GitHub	> w19	> Share > OK

