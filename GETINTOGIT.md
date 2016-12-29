
#Steps to use the github
####Step 1:
Create the github account by using below link [Join GitHub](https://github.com/join?source=header-home) and fill all the required feilds and verify the email address.

####Step 2: 
Sign in into your git hub account and create new repository 

####Step 3: 
Install Git in your local system 
for Ubuntu use the below command	

``sudo apt-get install git		``

for cent os by default it will be installed		

check and verfy the git version ``git --version`` expected output is the version of the git.		

####Step 4:
Configure the git account		

``git config --global user.name "your loginname"``		

``git config --global user.email "your email"``		

##Create One New Directory And Go Inside The Directory 
####Step 5:
Initialize the git by below command		

``git init``
####Step 6:
Add remote repository to local		

``git remote add origin httpurl``		
 
The http link you can get by web interface once you logged into the github select the repository and in the reight corner option will come up t
o clone or download select the option and url will be appeared,copy the url and replace the hhtp link with your http link.
step 7
 create one file with .md extension and add some content

#####How to upload the local file to repository??
``git add filename`` 		
replace filename with your filename		

``git commit -m "some commit message"``		

``git push origin master``

It will prompt the username and password give the creddentials.

