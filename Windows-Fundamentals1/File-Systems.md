Terms to understand:

        Alternate Data Streams (ADS)
        NTFS (New Technology File System)
        FAT16/FAT32 (File Allocation Table)
        HPFS (High Performance File System)


The file system used in modern versions of Windows is the New Technology File System or simply NTFS. 

NTFS is known as a journaling file system. In case of a failure, the file system can automatically repair the folders/files 
on disk using information stored in a log file. This function is not possible with FAT. (File Allocation Table)

<img src="https://assets.tryhackme.com/additional/win-fun1/win-file-system.gif">

How can you view the permissions for a file or folder?

    Right-click the file or folder you want to check for permissions.
    From the context menu, select Properties.
    Within Properties, click on the Security tab.
    In the Group or user names list, select the user, computer, or group whose permissions you want to view.

In the below image, you can see the permissions for the Users group for the Windows folder. 

![image](https://user-images.githubusercontent.com/104815254/226783751-ab06d297-0a42-43a9-9b4a-3212175c7de2.png)"

     
![image](https://user-images.githubusercontent.com/104815254/226784285-25920d09-80ce-49a0-bea3-57ac69d51445.png)



 <div style="<div style="text-align:center;width: 300px;margin: 0 auto;border-style: dotted;"> <h2>
        Beware! </h2> </div>

The Windows folder (C:\Windows) is traditionally known as the folder which contains the Windows operating system. 
