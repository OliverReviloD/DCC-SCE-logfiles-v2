Dell Command Configure 
- return values of CCTK.EXE are realted to the installed DCC version
- they are documented in the file(s)

![image](https://github.com/user-attachments/assets/4622e68f-8a82-45a4-9b51-bf888334aab6)

Adminstrator may use 'Dell Command Configure Wizard' ( CCTK-GUI ) to create SCE (Self Containing Executables) files as a kind of Setup-Wrapper. 
These SCE files ( they contain CCTK.EXE and Config.INI) can get started with a dedicated log file 
 
 <SCEExeFilePath> /l=<SCELogFilePath>

The SCE log files are returning with the ExitCode of the wrapper-Exe
They are only partly returning the ExitCode of CCTK itself
