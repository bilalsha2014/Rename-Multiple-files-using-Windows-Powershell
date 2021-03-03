# Rename-Multiple-files-using-Windows-Powershell
Rename specific characters from Multiple files and replace them with specified text using Powershell
get-childitem *.JPG | foreach {rename-item $_ $_.name.replace("_",";")}

write this code after * mention file extension 


 
