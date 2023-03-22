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



        Beware!

The Windows folder (C:\Windows) is traditionally known as the folder which contains the Windows operating system. 
        The C:\Windows folder is a critical part of the Windows operating system that contains essential files, settings, and programs. It is important because it helps Windows run smoothly and perform necessary tasks, such as managing hardware drivers and system updates. However, the C:\Windows folder can also be a dangerous place if accessed or modified by unauthorized users. This is because some of the files in this folder are crucial for the proper functioning of the operating system, and modifying or deleting them can cause serious damage to the system, including crashes, errors, and data loss. Additionally, malware and viruses often target this folder as a way to gain access to sensitive data or take control of the system. Therefore, it is important to exercise caution when accessing or modifying the C:\Windows folder, and to only do so with proper permissions and a thorough understanding of the potential risks involved.

        
        I. Introduction

    File system: a way of organizing and storing files on a computer
    Windows file systems: the file systems used by Microsoft Windows operating systems
    Importance of understanding file systems:
        Helps with troubleshooting and fixing errors
        Helps with organizing and managing files
        Crucial for cybersecurity, since file systems affect file access, permissions, and security

II. File systems in Windows

    FAT (File Allocation Table):
        Used in older versions of Windows (up to Windows 98)
        Simple and easy to implement, but has limitations:
            Limited file and partition size
            No built-in security features
    NTFS (New Technology File System):
        Introduced with Windows NT (1993)
        Offers many advanced features:
            Large file and partition sizes
            Built-in security features (file permissions, encryption, auditing)
            Better file compression and indexing
    Comparison between FAT and NTFS:
        NTFS is more advanced and secure, but requires more resources and is less compatible with other operating systems

III. Understanding file paths

    File path: the location of a file or folder on a computer
    Absolute vs. relative file paths:
        Absolute path: starts from the root directory (e.g. C:\Windows\System32)
        Relative path: starts from the current directory (e.g. .\Documents)
    Components of a file path:
        Drive letter: the letter assigned to a disk drive (e.g. C:)
        Folder names: the names of the directories that contain the file (e.g. Windows\System32)
        File name and extension: the name of the file (e.g. calc.exe)

IV. Tips for managing files in Windows

    Organizing files into folders:
        Helps with finding and accessing files
        Can use subfolders and categories for better organization
    Renaming, moving, copying, and deleting files:
        Right-click on file(s) to access options
        Use caution when deleting files, especially system files
    Recovering deleted files:
        Windows has a Recycle Bin that stores deleted files temporarily
        Third-party software can recover deleted files permanently
    Using compression and encryption:
        File compression can save disk space and make files easier to share
        Encryption can protect sensitive files from unauthorized access

V. Best practices for Windows file system security

    Setting permissions on files and folders:
        Use least privilege principle (only give access that is necessary)
        Be careful when changing permissions on system files
    Using encryption to protect sensitive files:
        Use BitLocker (built-in encryption tool) for system drives
        Use third-party encryption software for files and folders
    Backing up important data:
        Use a backup solution (e.g. Windows Backup and Restore)
        Store backups offsite or in the cloud
    Scanning for malware and viruses:
        Use antivirus software and keep it up to date
        Be careful when downloading and installing software
    Staying up to date with software and security patches:
        Install Windows updates and security patches regularly
        Keep third-party software up to date to avoid vulnerabilities

VI. Conclusion

    Windows file systems are important for organizing and managing files, as well as for cybersecurity
    Understanding file paths and file management techniques can make working with files easier and more efficient
    Best practices for file system security can help protect your data and prevent unauthorized access
    Additional resources for learning more about Windows file systems and cybersecurity include online tutorials, books, and courses.
