#  CHOCOLATEY
The sane way to manage software on Windows.

Irritated with installing desktop programs on your system from a website,by downloading an EXE or MSI file, and then clicking all the way through the installation. That is an easy, but time consuming.

Well, here is when, **"Chocolatey"** works as a saviour.

Chocolatey installs desktop apps without having to click through an interminable number of installation windows.





 ## STEPS TO INSTALL CHOCOLATEY -

1. Go to https://chocolatey.org. Click on "Install Chocolatey Now" and follow the instructions OR
2. There are two ways of installing -:
    1. **USING POWER SHELL**  
     
       ```
       1. Open powershell in administration mode.
            - Type powershell in search and right click and select run as administrator. 
                                        OR
            - Type powershell in search and press ctrl+shift+enter.
        2. Paste iwr https://chocolatey.org/install.ps1 -UseBasicParsing | iex and hit enter.
        ```
       
  
   
   2. **USING CMD PROMPT**
   
   ```
        1. Open cmd prompt in administration mode.
            - Type cmd prompt in search and right click and select run as administrator.  
                                      OR
            - Type cmd prompt in search and press ctrl+shift+enter.
        2. Paste @powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
            and hit enter.
            ```
            
            
           

## USING CHOCOLATEY -

1. Again open the powershell/cmd prompt in admin mode.
2. Go to https://chocolatey.org/packages and select a software to download.
3. For installing use the cmd - "cinst", for unistalling use "cunist".
4. Example - "cinst vlc" for installing. "cunist vlc" to unistall. "choco upgrade all" to upgrade all.


**NOTE** : While installing, you have to give the exact name , for example to download notepad++, you need to give "cinst notepadplusplus".





## COMMANDS FOR USING CHOCOLATEY -

You can find the list of commands and documentation at https://chocolatey.org/docs/commands-reference or simply type "choco -h" from  powershell/cmd prompt in admin mode, once you have CHOCOLATEY installed.
   
 CHOCOLATEY IS AN EASY WAY OF AVOIDING UNNECESSARY CLICKS AND QUICKLY INSTALLING APPLICATIONS AND TOOLS THAT YOU NEED.    
