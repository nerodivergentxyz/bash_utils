# bash_utils
miscellaneous bash scripts i've made while using linux
## tar unpackager script
automated tar file unpackaging and desktop menu entry creation. can be used for initial installs and subsequent updates
### filetypes supported: .tar, .tar.gz, .tar.bz2, 
```bash
➜  ~ ./tar_dpkg.sh Downloads/code-stable-x64-1728492644.tar.gz 
Starting installation/update process for Downloads/code-stable-x64-1728492644.tar.gz...
Creating/Updating target directory Downloads/code-stable-x64-1728492644.tar...
Cleaning up old files in Downloads/code-stable-x64-1728492644.tar...
Extracting Downloads/code-stable-x64-1728492644.tar.gz...
Extraction completed.
Navigated into Downloads/code-stable-x64-1728492644.tar.
Searching for the first executable...
Executable found: ./VSCode-linux-x64/libffmpeg.so
Parsed application name: code
Checking for an icon named after the application...
Found named icon: /home/jj/Downloads/code-stable-x64-1728492644.tar/./VSCode-linux-x64/resources/app/resources/linux/code.png
Creating/Updating a desktop entry for code...
Desktop entry created/updated: /home/jj/.local/share/applications/code.desktop
Application code installed/updated successfully!

```
