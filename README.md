THIS PROGRAM MUST RUN FROM YOUR KSP CLIENT OR DMP SERVER DIRECTORY.  
  
This is a command line program that will update the DMP client or server for you.  
  
This program will automatically detect if it's in the server or client directory and update the files accordingly.  
  
This program uses sha256sum indexes, so it will only download files that have changed.  
  
If it doesn't find a "-version" part in the filename, it will default to using the release version.  
  
To switch it to the version, rename the executable to DMPUpdater-version.exe,  
where version is one of the versions listed in http://godarklight.info.tm/dmp/updater/index.txt  
  
This program takes one command line option: --batch or -b, which will make it exit without asking.  
