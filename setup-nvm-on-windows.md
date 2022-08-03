# Setup Node Version Manager in Windows

Visit the following page of [NVM](https://github.com/coreybutler/nvm-windows/releases)

``` 
https://github.com/coreybutler/nvm-windows/releases
```
&nbsp;

Download and Extract latest nvm-setup.zip 
```
https://github.com/coreybutler/nvm-windows/releases/download/1.1.9/nvm-setup.zip
```
&nbsp;

In the nvm-setup folder, double-click on nvm-setup.exe and complete the instructions with all default values.

&nbsp;

To confirm nvm is installed successfully, check the version of nvm in the terminal

```
nvm -v
```
&nbsp;

# How to use NVM on windows

lists all node versions installed on your system
```
nvm list
```

install the node version you want (in this case version 14.17.3)
```
nvm install v14.17.3
```

select the node version you want to use 
```
nvm use v14.0.0
```

Note: (*) indicates the the current node version being used
```
nvm list 
18.3.0 
*14.17.3 (Currently using 64-bit executable)
```

