# Powershell-Cheat-Sheet
### Some useful commands

### File files givem a certain extension and get their content
    ForEach ($files in Get-ChildItem -Force -recurse){if ($files -Like "*.txt"){echo $files | Get-Content}}
    
### Encode file content in b64
    [convert]::ToBase64String((gc file.txt -Encoding byte))
