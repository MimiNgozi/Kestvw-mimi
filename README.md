# Kestvw-mimi
# Lokaverfni
### To make the users
$username = Read-Host "Enter your username"
$fullname = Read-Host "Enter your full name"
$pass = Read-Host "Enter your password" -AsSecureString
New-LocalUser -name $username -FullName $fullname -Password $pass -Description "For lokaverkefni"
### Making groups
$Gname = Read-Host "Enter your Groupname"
New-LocalGroup $Gname

###  Adding to groups
Add-LocalGroupMember -Group Users  -Member ninam
* Senior management==
   * Masi , Mason Young
   * Grey , Gary Cole

* Marketing==

    * Sussi , Susan Connor
    * Rickki , Rick  Novak
    * Lilli , Liam Peter
    * Willi- willam long 

* Sales ==
    * Xasi , Xabi Alsono
    * Oliva , Olivia Perry
    * Ronni, Ronald Barr

when the 4 folders are made
for management 
* Management Properites > Security (tab) > Edit > Add ( all the groups ) 
allow full contol for the mangnement team then for the other teams deny 
hen do the rest for the rest of the groups


