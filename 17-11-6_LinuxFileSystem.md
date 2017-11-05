# Linux ~intro to filesystem and bash
Shell prompt format
```
username@hostname:current_directory
```
* $ -user prompt
* \# -root prompt  
type 'man _command_' to see the manuscript of how to use almost any command/program  
type 'man hier' for a description of every system directory

## Files
Not case sensitive  
Use **file** to get infos


#### Hidden Files
Start with a dot 


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

### All commands used in the order they were presented
* **Note: ~ is your home directory**
*    **tab key does autocomplete**
* pwd
* ls -a -l
* mkdir and rmdir
* touch
* history
* echo
* cat
* chmod + -
