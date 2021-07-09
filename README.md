# runPHP-CommandlineReferences
runPHP-Commandline References

Run PHP Git Bash/CLI

Go to directory where PHP installed.
<br /> Example Wamp64 Server:
<br /> C:\wamp64\bin\php\php7.4.9
<br /> 
<br /> Xampp Server:
<br /> C:\xampp\php
<br /> 
<br /> Note: Make sure you find the php application icon on the directory
<br /> 
Go to "My Computer" // rightclick
<br /> > System Properties 
<br /> > Advanced // tab
<br /> > Environment Variable // button
<br /> 
<br /> > User variable for admin
<br /> > Path 
<br />  → Double click
<br />  → New 
<br />  → Paste php directory // C:\xampp\php
<br />  → Click Ok
<br /> > New... // button
<br />  → Variable name: any
<br />  → Variable Value: C:\xampp\php
<br /> 
<br /> > Click Ok
<br /> > System Properties Click Ok
<br />
Run: CMD/CLi/GitBash 
<br />admin@DESKTOP-08MNQ2P MINGW64 /c/wamp64/www/phg
<br />$ php file.php
<br />
<br /> // include file index.php have function getUserList() {  // ; }
<br />$ php -r 'include "index.php"; print getUserList();' // include file function and calling specific the function
<br />
<br />$ php -a
<br />Interactive shell
<br />
<br />php > require 'index.php'; // require file
<br />php > getUserList();  // calling the function within the require file
<br /> Output: string(4) "Tea" // output
<br /> php >
<br /> php > quit

