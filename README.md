# glutSetup

A guide to help glut beginners to setup glut in Visual Studio 2019

1. Download and extract the zip from ==https://www.mediafire.com/file/cmlnr0pj0pyha5d/Glew_and_Glut.zip/file==
2. Create an empty project in Visual Studio 2019
3. Find solution explorer
4. Right click solution explorer and click properties
5. Navigate to C/C++ -> General, click on Additional Include Directories
6. Add the ==freeglut\include== folder path
7. Navigate to Linker -> General, click on Additional Library Directories
8. Add the ==freeglut\lib== folder path
9. Navigate to Linker -> Advanced, click on Entry Point and enter ==mainCRTStartup==
10. Click apply and ok
11. copy the ==freeglut\bin\freeglut.dll== and paste to ==C:\Windows\SysWOW64\==
