# Kestvw-mimi
# Lokaverfni
### To make the users
$username = Read-Host "Enter your username"
$fullname = Read-Host "Enter your full name"
$pass = Read-Host "Enter your password" -AsSecureString
New-LocalUser -name $username -FullName $fullname -Password $pass -Description "For lokaverkefni"
### M aking groups
$Gname = Read-Host "Enter your Groupname"
New-LocalGroup $Gname

###  adding to groups
Add-LocalGroupMember -Group Users -Member ninam