# Example Install
This is the expected output if you are a user 'stcollier'

```
stcollier@StefTop:~/Git/gimme$ ./install_gimme.sh 
==================================
         Running Checks
==================================
+Installer running in correct pwd  [Pass]

==================================
         Installing gimme
==================================
+Making folders
mkdir: cannot create directory /home/stcollier/.stools_config: File exists
mkdir: cannot create directory /home/stcollier/.stools_config/gimme: File exists
+Creating files
+Creating function file
install_gimme: Install complete

==================================
  Add this line to your .bashrc:
==================================
If you don't, the command won't be in scope!

source ~/.stools_config/gimme/gimme_function.sh
```
