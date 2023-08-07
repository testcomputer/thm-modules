You will practice web penatration testing using the command line tool, Gobuster.

    gobuster -u http://fakebank.com -w wordlist.txt dir

The command will run and show you an output similar to this:

GoBuster command to brute-force website pages
     
      ubuntu@tryhackme:~/Desktop$ gobuster -u http://fakebank.com -w wordlist.txt dir
      =====================================================
      Gobuster v2.0.1
      =====================================================
      [+] Mode         : dir
      [+] Url/Domain   : http://fakebank.com/
      [+] Threads      : 10
      [+] Wordlist     : wordlist.txt
      [+] Status codes : 200,204,301,302,307,403
      [+] Timeout      : 10s
      =====================================================
      2022/04/11 18:23:28 Starting gobuster
      =====================================================
      /images (Status: 301)
      /DIRECTORY_NAME_OUTPUT (Status: 200)
      =====================================================
      2022/04/11 18:23:38 Finished
      =====================================================

Using Gobuster with the -u and -w flags allows you to perform directory and file brute-force attacks against a target website or web server. Gobuster is a tool designed for directory and file enumeration, and these flags enhance its functionality:

-u flag: Specifies the target URL to be scanned. This is the base URL of the website where Gobuster will attempt to find hidden directories and files. For example:

    gobuster dir -u http://example.com

-w flag: Specifies the path to the wordlist file containing a list of words or directory and file names that Gobuster will use for brute-forcing. Gobuster will combine the words from the wordlist with the target URL to generate different paths to test. For example:

    gobuster dir -u http://example.com -w /path/to/wordlist.txt

Here's how the combination of -u and -w works:

You provide the -u flag followed by the target URL you want to scan.

You provide the -w flag followed by the path to a wordlist file containing potential directory and file names.

Gobuster combines each word from the wordlist with the target URL, creating different paths to test. For instance, if the wordlist contains "admin" and the target URL is http://example.com, Gobuster will test http://example.com/admin to see if the directory or file exists.

Gobuster sends HTTP requests for each generated path, checking for valid responses from the server. If a response indicates that the path exists (e.g., HTTP status code 200), Gobuster reports the finding.

By using the -u and -w flags, you can efficiently search for hidden directories and files on a web server. This is useful for discovering potential security vulnerabilities, misconfigurations, or sensitive information that might be exposed unintentionally. However, it's important to use tools like Gobuster responsibly and only on systems for which you have proper authorization.      

![image](https://github.com/testcomputer/TryHackMe-Modules/assets/104815254/6220e4e6-9df3-4e6d-b6e7-78de744089a5)

   
The web application will read the data about the products and their details from a database server. A database is used to store 
information in an organized way. Examples include information about products, customers, and invoices. A database server is 
responsible for many functions, including reading, searching, and writing to the database.


Products database: This database contains details about the products, such as name, images, specifications, and price.
Customers database: It contains all details related to customers, such as name, address, email, and phone number.
Sales database: We expect to see what each customer has purchased and how they paid in this database.


![image](https://github.com/testcomputer/TryHackMe-Modules/assets/104815254/9bfca321-a8f0-424a-80a3-32bef8aa1f9f)


