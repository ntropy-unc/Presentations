# Linux ~ intro to the linux filesystem and bash
Shell prompt format
```
username@hostname:current_directory
```
* $ -user prompt
* \# -root prompt  
type 'man _command_' to see the manuscript of how to use almost any command/program  
type 'whatis _command_' for a concise description of what the command does.
type 'man hier' for a description of every system directory

## Files
Not case sensitive  
Use **file** command to see what kind of file

#### Hidden Files
aka dot files
Start with a dot  
ctrl-h -to see these graphically  
ls -a  -to see these in the terminal  

## Permissions 
Each character represent a different permission: 
* r: readable 
* w: writable 
* x: executable (basically an executable program) 
* -: empty  
other permission bits  
  * s: SUID ~ set user id
  * t: Sticky Bit ~ only owner or root can delete/modify files
```
ls -l
-rwxr-xr-x 1 user group 0 Nov  6 17:43 testFile.txt
```
Format:  
fileType | user | group | others | user-name | group-name | time-last-modified | file-name
d ~ directory  
- ~ regular file  

Numerical Representations
* 4: read permission
* 2: write permission
* 1: execute permission

### Resources  
https://distrowatch.com/  
https://en.wikipedia.org/wiki/Usage_share_of_operating_systems  
https://linuxjourney.com/  
https://linuxconfig.org/filesystem-basics  
https://www.youtube.com/watch?v=HIXzJ3Rz9po

### All commands used in the order they were presented
* **Note: ~ represents the home directory**
*    **tab key does autocomplete**
* pwd
* ls -a -l
* mkdir and rmdir
* touch
* history
* echo
* cat
* chmod + -
* exit
