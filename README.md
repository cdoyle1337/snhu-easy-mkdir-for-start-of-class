# snhu-easy-mkdir-for-start-of-class
easily make folders for start of class with powershell

##This is a bit of code you can run in Powershell to create your SNHU Course folders easily. Change your course name or module name to suit your needs. I also included a screenshots folder which can be removed if desired.


cd .\Documents\ 
md SNHU 
cd .\SNHU\ 
MD CS-210 
cd .\CS-210\ 
for ($i=1;$i -le 8;$i++){MD ".\Module 0$i"; MD ".\Module 0$i\Screenshots"} 

## or you can run it without screenshots folder:
for ($i=1;$i -le 8;$i++){MD ".\Module 0$i"} 
