# How to install pyhton
1. install python
- check python verion
```
python -V
```
- if error: you should check python path on environment(windows)

2. create folder to store project
- open folder using cmd
3. create virtual environment for python (2 ways)
## using cmd
```
python -m venv <env_name>
```
## using vscode
```
press: ctrl+p
- type: >python create env
- select: venv create
```
4. activate .venv
- Change the Execution Policy:
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```
- activate .venv cd D:\PythonDev\python_fastapi
```
.\.venv\Scripts\Activate
```
- deactivate
```
deactivate
```
<p><img src="screenshort\activate venv.png"></p>