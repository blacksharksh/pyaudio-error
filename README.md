# pyaudio-error



C:\Users\mohanSharma>python -m pip install pyaudio
Collecting pyaudio
  Using cached https://files.pythonhosted.org/packages/ab/42/b4f04721c5c5bfc196ce156b3c768998ef8c0ae3654ed29ea5020c749a6b/PyAudio-0.2.11.tar.gz
Installing collected packages: pyaudio
  Running setup.py install for pyaudio ... error
    ERROR: Command errored out with exit status 1:
     command: 'C:\Users\mohanSharma\AppData\Local\Programs\Python\Python37\python.exe' -u -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\MOHANS~1\\AppData\\Local\\Temp\\pip-install-ysn6m91l\\pyaudio\\setup.py'"'"'; __file__='"'"'C:\\Users\\MOHANS~1\\AppData\\Local\\Temp\\pip-install-ysn6m91l\\pyaudio\\setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record 'C:\Users\MOHANS~1\AppData\Local\Temp\pip-record-26_jshod\install-record.txt' --single-version-externally-managed --compile
         cwd: C:\Users\MOHANS~1\AppData\Local\Temp\pip-install-ysn6m91l\pyaudio\
    Complete output (9 lines):
    running install
    running build
    running build_py
    creating build
    creating build\lib.win-amd64-3.7
    copying src\pyaudio.py -> build\lib.win-amd64-3.7
    running build_ext
    building '_portaudio' extension
    error: Microsoft Visual C++ 14.0 is required. Get it with "Microsoft Visual C++ Build Tools": https://visualstudio.microsoft.com/downloads/
    ----------------------------------------
ERROR: Command errored out with exit status 1: 'C:\Users\mohanSharma\AppData\Local\Programs\Python\Python37\python.exe' -u -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\MOHANS~1\\AppData\\Local\\Temp\\pip-install-ysn6m91l\\pyaudio\\setup.py'"'"'; __file__='"'"'C:\\Users\\MOHANS~1\\AppData\\Local\\Temp\\pip-install-ysn6m91l\\pyaudio\\setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record 'C:\Users\MOHANS~1\AppData\Local\Temp\pip-record-26_jshod\install-record.txt' --single-version-externally-managed --compile Check the logs for full command output.
WARNING: You are using pip version 19.2.3, however version 21.0.1 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.
