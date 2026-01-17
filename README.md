FOR POWERSHELL

(Invoke-WebRequest 'https://raw.githubusercontent.com/SnehalSonawane123/DSBDA/main/1.txt' -UseBasicParsing).Content -replace "`r`n"," "
