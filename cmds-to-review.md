# CMD Line Review/Practice

# Linux
## General CMDS
        whoami
        ssh USERNAME@10.10.182.96
        ls	listing
        cd	change directory
        cat	FILENAME (concatenate)
        pwd	print working directory
        find -name passwords.txt
        history # (# = number of cmds run)
        grep "item-to-search-for" filename.txt (search the contents of files for specific values)
## OPERATORS


    Operator "&" 
        run commands in the background of your terminal

    Operator "&&"	
        combine multiple commands together in one line of your  terminal.

    Operator ">" 
        output redirector

        example:
            tryhackme@linux1:~$ cat welcome
            hey
            cat welcome
            hey

        NOTE: If the file i.e. "welcome" already exists, the contents will be overwritten!


    Operator ">>"  
        same function of the > operator but appends the output rather than replacing (meaning nothing is overwritten).
