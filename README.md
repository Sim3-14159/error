# ${\\color{orange}{\text{ERROR}}}$
Filesystem deletion in progress at [Sim3-14159.github.io/error](https://Sim3-14159.github.io/error).

(A joke)

---
<br>

### If you want to scare somebody, run one of these commands ${\\color{grey}{\text{(Don't worry, these commands are harmless)}}}$:

##### Windows Powershell
```powershell
Start-Job -ScriptBlock { Get-ChildItem -Path C:\ -Recurse -Force -ErrorAction SilentlyContinue | ForEach-Object { "Deleting $($_.FullName)" } } | Out-Null; Start-Job -ScriptBlock { 1..1000 | ForEach-Object { "ERROR" } } | Out-Null; Start-Process "https://Sim3-14159.github.io/error"
```

#####   Windows Command Prompt
```powershell
powershell -Command "Start-Job -ScriptBlock { Get-ChildItem -Path C:\ -Recurse -Force -ErrorAction SilentlyContinue | ForEach-Object { \"Deleting $($_.FullName)\" } } | Out-Null; Start-Job -ScriptBlock { 1..1000 | ForEach-Object { \"ERROR\" } } | Out-Null; Start-Process \"https://Sim3-14159.github.io/error\""
```

##### MacOS/Linux Terminal
```bash
( sudo find / -print0 | xargs -0 -I{} echo "Deleting "{}) & ( for i in $(seq 1 1000); do echo "ERROR"; done ) & ( open "https://Sim3-14159.github.io/error" >/dev/null 2>&1 ) & wait
```
