# Powershell-Cheat-Sheet
### Some useful commands
    ForEach ($files in Get-ChildItem -Force -recurse){if ($files -Like "*.txt"){echo $files | Get-Content}}
