Helpico Core 1.0.1
===============================

Site:https://helpico.io/ <br>
Block explorer:https://helpico.tech/

Bootstrap
===============================
Close the Helpico Core client <br>
Remove folders:
- blocks
- chainstate
- database
Remove Files:
- peers.dat
- banlist.dat <br>
Download and unzip the bootstrap.dat file to the directory
```
$ helpico-cli stop
$ cd ~/.helpicocore
$ rm -r blocks
$ rm -r chainstate
$ rm -r database
$ rm peers.dat
$ rm banlist.dat
$ wget https://github.com/AnonymousDo/Helpico/releases/download/v1.0.1/bootstrap.dat.zip
$ unzip bootstrap.dat.zip
$ helpicod
```
Windows default folder 
`%APPDATA%/HelpicoCore`<br>
MacOS default folder
`~/Library/Application Support/HelpicoCore`<br>
Linux default folder
`~/.helpicocore`<br>
