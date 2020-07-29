# Variables vs Environment Variables 

The **environment** provides a medium through which the shell process can get or set settings and, in turn, pass these on to its child processes.

The **environment** is implemented as strings that represent key-value pairs. If mulitple values are passed, they are separated by colon **(:)** characters.

**Environmental variables** are variables that are defined for the current shell and are inherited by any child or processes. Environmental variables are used to pass information into processes that are spawned from the shell. 

**Shell variables** are variables that are contained exclusively within the shell in which they were set or defined. They are often used to keep track of ephemeral data, like the current working directory. 


Creating variables in Linux 
```bash
name="Anais"
```

Displaying variable value 
```bash
echo $name
```

Exporting variables to our environment 
```bash
export name="Anais"
```

Checking our env 
```bash
env
```


