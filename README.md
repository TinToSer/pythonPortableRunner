# pythonPortableRunner

## Feel the power of Interpreter as Portable Interpreter
A standalone Python Executable to Run your Python scripts so that You can distribute Python code directly .It simply uses Python exec() to run your code.


As a servant of Science my responsibility is to make Python Modules available as magic executable so you don't have worry about installation of modules and setting things

You just write Python code ,may be black box or share it open.

It automatically put your Python file location in its Environment so the package and other modules if used is simply recognised to work

                Python Portable Runner

                          Developed By:- TinToSer
                                            (https://github.com/tintoser)

usage: pythonPortableRunner.exe [-h] [--MainFile MAINFILE]
                                [--PackageFolder [PACKAGEFOLDER]]

optional arguments:
  -h, --help            show this help message and exit
  --MainFile MAINFILE   Enter the main python file to run your program
  --PackageFolder [PACKAGEFOLDER]
                        Enter the absolute folder path if your package and
                        modules are in different folder,if many then comma
                        separated

Example of usage:- 
		pythonPortableRunner.exe --MainFile=main.py