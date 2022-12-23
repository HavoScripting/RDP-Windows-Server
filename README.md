# WINRDP
How to use 

Just Fork this Repository, Go to Actions tab, Select the Windows-CRD workflow. Then select Run Workflow fill the following data in CRD Code and your Pin in the fields. After that, Press Start.

Input the following code in the fields.

Get the Windows (Powershell) command from here:

https://remotedesktop.google.com/headless

==================================================================

& "${Env:PROGRAMFILES(X86)}\Google\Chrome Remote Desktop\CurrentVersion\remoting_start_host.exe" --code="4/0AWgavdfqxKAT_Cwntbt0E6tmQ7124j34AS2KH8MVN8dLTdIAVd5-i2L9YtCQAEAS4khAYA" --redirect-url="https://remotedesktop.google.com/_/oauthredirect" --name=$Env:COMPUTERNAME

==================================================================

Enter you Six digit Pin code to Login

(Any Six digit Pin)

Thats it... After 2-3 min of Initialize, Check your CRD Application or Account.
