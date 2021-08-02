<h1>Convert python file to executable</h1>

First install [pyinstaller](https://www.pyinstaller.org/documentation.html)  
`pip install pyinstaller`

The command below tells pyinstaller not to display Command Prompt window when exe is launched and it renames the executable to hardware.exe    
`pyinstaller --onefile -w tcpclient_v5.py --name "hardware.exe"`


