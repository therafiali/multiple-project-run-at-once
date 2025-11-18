Save the above script as "run.bat" file
Double-click the file, and it will open two separate terminals: one for backend, one for frontend.



```
@echo off
echo Starting Feedback Portal Backend...
start cmd /k "cd /d C:\Users\abcd\rafi\feedback-portal\backend && npm run dev"

echo Starting Feedback Portal Frontend...
start cmd /k "cd /d C:\Users\abcd\rafi\feedback-portal\frontend && npm run dev"
```
