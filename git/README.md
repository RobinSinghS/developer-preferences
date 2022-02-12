# There is two easy way to set the alias.

  1. Using Bash
  2. Updating .gitconfig file

## Using Bash
Open bash terminal and type git command. For instance:

```
$ git config --global alias.a add
$ git config --global alias.aa 'add .'
...
...
```
It will eventually add those aliases on .gitconfig file.

## Updating .gitconfig file

Open .gitconfig file located at 'C:\Users\username\.gitconfig' in Windows environment. 
Then add following lines:

```
[alias]  
  a = add  
  aa = add . 
  ....
```  
