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

5. Activate venv and install any necessary 
```
python -m pip install fastapi
```
- upgrade pip
```
python.exe -m pip install --upgrade pip
``` 
<p><img src="screenshort\install fastapi.png"></p>
- create main.py
6. run server 
```
uvicorn main:app --host "0.0.0.0" --port 8000 --reload
```
- result
<p><img src="screenshort\uvicorn serve.png"></p>
- fastapi docs: see all enpoint like postman tools
<p><img src="screenshort\fastapi docs.png"></p>

7. test web in terminal
- install package
```
python -m pip install httpie

http --version
```
- add terminal and run output
```
http localhost:8000
or 
http GET http://localhost:8000/
```
<p><img src="screenshort\test output in terminal.png"></p>