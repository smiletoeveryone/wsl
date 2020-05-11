# run ubuntu bash in your windows 10

 ![](https://github.com/smiletoeveryone/wsl/blob/master/ubuntustore.png)
 
 run PowerShell as administrator
 
 ![](https://github.com/smiletoeveryone/wsl/blob/master/How-to-open-an-elevated-PowerShell-prompt.jpg)


#Enable WSL(Windows Subsystem for Linux) in windows 10

    1. run PowerShell as administrator
  
    right click on winx menu >> search >> type powershell >> run as administrator

    2.Enable WSL(Windows Subsystem for Linux)

    in powershell 

    c:>Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux

    3. reboot windows 

    4. after rebooting

    get into Microsoft Store >> search bar >> type ubuntu

    a1. choice what edition of ubuntu you like // Ubuntu 18.04 LTS is recommended.

    a2. install it

    a3. launch it


    5. done
    
#install jupyter notebook in WSL(Windows Subsystem for Linux) 


    1. sudo apt update && upgrade
    
    2. sudo apt install python3 python3-pip ipython3
    
    3. sudo apt install python3-pip
    
    4. sudo pip3 install jupyter // install all the packages
    
    5. sudo pip3 install jupyter-notebook
    
    6. run the command "jupyter-notebook" in the terminal 
    
    7. done
    
