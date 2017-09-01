# Aggressor Scripts
Collection of Aggressor scripts for Cobalt Strike 3.0+ pulled from multiple sources
* All_In_One.cna v1
    
   * All purpose script to enhance the user's experience with cobaltstrike. Custom menu creation, Logging, Persistence,        Enumeration, and 3rd party script integration.
   * Thanks to @rsmudge, @enigma0x3, @harmj0y, PowerShell Mafia folks, Nathan Wray, @Und3rFl0w, @oldb00t, bluescreenofjeff for all the help and code snippets.
   * Script must reside in /opt/cobaltstrike/ directory. (Location can be changed inside the script)

**All_In_One.cna Dependencies:**

    Parent Folder/Files: 
        /opt/cobaltstrike/All_In_One.cna
        /opt/cobaltstrike/av_hips_executables.txt 
        /opt/cobaltstrike/logs.py
    Sub Folders: 
        /opt/cobaltstrike/scripts/
        /opt/cobaltstrike/Payloads/
        /opt/cobaltstrike/modules/
    Elevate Kit (Licensed Users Only)
    
* ArtifactPayloadGenerator.cna

    * Generates every type of Stageless/Staged Payload based off a HTTP/HTTPS Listener
    
    * Creates /opt/cobaltstrike/Staged_Payloads, /opt/cobaltstrike/Stageless_Payloads
    
* AVQuery.cna

    * Queries the Registry with powershell for all AV Installed on the target
    
    * Quick and easy way to get the AV you are dealing with as an attacker
    
    ![av](https://user-images.githubusercontent.com/27856212/28275624-7331ab2e-6ae2-11e7-8405-3393e917863e.png)
