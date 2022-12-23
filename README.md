# WINRDP
How to use 

Just Fork this Repository, Go to Actions tab, Select the Windows-CRD workflow. Then select Run Workflow fill the following data in CRD Code and your Pin in the fields. After that, Press Start.

Input the following code in the fields.

Get the Windows ( PowerShell ) command from here:

https://remotedesktop.google.com/headless

Enter you Six digit Pin code to Login

(Any Six digit Pin)

Thats it... After 2-3 min of Initialize, Check your CRD Application or Account.


##############################################################################################
    =================================( Havo Scripting )====================================
1. OPEN A GITHUB ACCOUNT
2. FORK https://github.com/HavoScripting/shakrdp
3. GO TO ACTIONS
4. CREATE A NEW WORKFLOW
5. GO TO https://remotedesktop.google.com/headless AND COPY THE POWERSHELL SCRIPT
6. PASTE THE POWERSHELL SCRIPT IN THE WORKFLOW
7. ENTER A PIN ANY YOU WANT
8. CLICK RUN
9. GO TO https://remotedesktop.google.com/access AND ENTER THE PIN

7GB RAM
2 CPU
255 GB HDD
Windows Server 2019
Download speed 900Mb/s

##############################################################################################
===[ Windows (Cmd) ]
"%PROGRAMFILES(X86)%\Google\Chrome Remote Desktop\CurrentVersion\remoting_start_host.exe" --code="4/0AWgavdc7vvwYE2PkDmAcIcMH6OwgVfimL-VtAZTiJyo9iDPKnHnbyPK6sKNpvXvg8yEV2g" --redirect-url="https://remotedesktop.google.com/_/oauthredirect" --name=%COMPUTERNAME%
----------------------------------------------------------------------------------------------
===[ Windows (PowerShell) ]
& "${Env:PROGRAMFILES(X86)}\Google\Chrome Remote Desktop\CurrentVersion\remoting_start_host.exe" --code="4/0AWgavdc7vvwYE2PkDmAcIcMH6OwgVfimL-VtAZTiJyo9iDPKnHnbyPK6sKNpvXvg8yEV2g" --redirect-url="https://remotedesktop.google.com/_/oauthredirect" --name=$Env:COMPUTERNAME
-----------------------------------------------------------------------------------------------
===[ Debian Linux ] 
DISPLAY= /opt/google/chrome-remote-desktop/start-host --code="4/0AWgavdc7vvwYE2PkDmAcIcMH6OwgVfimL-VtAZTiJyo9iDPKnHnbyPK6sKNpvXvg8yEV2g" --redirect-url="https://remotedesktop.google.com/_/oauthredirect" --name=$(hostname)
-----------------------------------------------------------------------------------------------
##############################################################################################

