## In Linux, file attributes refer to special flags that control how the system handles files beyond standard read, write, and execute permissions. The two primary commands for managing these are lsattr and chattr. ##
## lsattr (List Attributes): Displays the current attributes set on a file or directory. ##
## lsattr [filename] - Shows the shorthand flags (e.g., ----i---------). ##
## lsattr -l - Displays the full names of the attributes (e.g., "Immutable"). ##
## lsattr -R - Recursively lists attributes in directories. ##
## chattr (Change Attribute): Modifies the attributes of a file or directory. ##
## Syntax: sudo chattr [operator][flag] [filename].Operators: + (add), - (remove), or = (set exactly). ##

<img width="506" height="345" alt="File_Attribute_01" src="https://github.com/user-attachments/assets/2eb0dc1c-d2db-4a92-b6fa-1c59b0e0e415" />
<img width="469" height="268" alt="File_Attribute_02" src="https://github.com/user-attachments/assets/a1293409-2882-4ee0-8620-879e7d31e693" />
<img width="449" height="323" alt="File_Attribute_03" src="https://github.com/user-attachments/assets/8abb2e1f-ddf8-4679-aeac-05ec22da21a3" />
<img width="454" height="260" alt="File_Attribute_04" src="https://github.com/user-attachments/assets/7054db6d-b5fc-4d52-80d0-de50ccdf2ca1" />

