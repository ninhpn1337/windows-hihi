Chính chủ từ MS windows 11, up lên đây để win 10 dùng được.
source: https://github.com/microsoft/sudo

Lỗi: 
C:\Users\Administrator>sudo 
Sudo is disabled on this machine. To enable it, go to the Developer Settings page in the Settings app C:\Users\Administrator>


bật cmd
```
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Sudo" /v "Enabled" /t REG_DWORD /d 2 /f
copy tree.com ls.exe
```
