# File-permission-in-Linux
Just a portfolio explaining the uses of Linux commands

**chmod - The chmod command, short for "change mode," is a fundamental command in Unix and Unix-like operating systems, including Linux. It is used to modify the access permissions of files and directories.** 

***Key Concepts***

Owner permissions: Permissions for the owner of the file.
Group permissions: Permissions for the group associated with the file.
Other permissions: Permissions for all other users on the system.

Types of permissions that can be granted

Read (r) - permission allows viewing the content of a file or directory.

Write (w) - permission allows modifying or deleting a file or directory.

Execute (x) -  permission allows running a file as a program or accessing the contents of a directory. 

*Important tips*
- Read (r) permission enables users to open and view the contents of a file without altering it.
- Write (w) permission grants the ability to modify, delete, or rename a file or directory.
- Execute (x) permission is required to execute a file as a program or script.
- Read (r) permission is represented by the number 4 in octal notation.
- Write (w) permission is represented by the number 2 in octal notation.
- Execute (x) permission is represented by the number 1 in octal notation.
- With read (r) permission alone, a user can list files within a directory but cannot access their contents.
- Write (w) permission allows users to delete a file without viewing or modifying its contents.
- Execute (x) permission alone grants the ability to traverse into a directory but not list its contents.
- Users cannot access files or subdirectories without executing (x) permission on a directory.
- Combining read (r) and write (w) permissions allows complete control over a file, including modifying its contents.
- Combining read (r) and execute (x) permissions on a file allows it to be read and executed as a program.

  You can view the permissions of a file by using the ls -l command. This may not show the permissions of the hidden files. To view the permissions of the hidden files, we can use the ls -a command. To view both 
  collectively, use ls -la.

  *Changing Permissions*
  
- "+": Adds the specified permissions.
- "-": Removes the specified permissions.
- "=": Sets the specified permissions.

**Syntax** 
chmod permission_class + previledge, file_name

