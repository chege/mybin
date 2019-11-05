# mybin
This is just a collection of executables located in my bin folder, typically developer tools and such

## fswatch_notify
Notify when a file has changed and run a command

```
usage: /Users/christopher/bin/fswatch_notify [file] [command]
```

```bash
$ fswatch_notify ~/.bashrc source .bashrc
# Executes .bashrc when .bashrc is modified
```


## lower
Converts the input string to lowercase

```bash
$ lower JUST BECAUSE I HAVE TO GOOGLE IT
# echos 'just because i have to google it'
```

## tounderscore
Concatenate arguments with underscore in between

```bash
$ toundercore I really need to improve my bash skills
# echos 'I_really_need_to_improve_my_bash_skills'
```

## printjsondot
Print JSON file(s) using dot notations. 

````bash
usage: printjsondot [-h] file [file ...]
````

```bash
$ printjsondot xanadu/honeydew.json
```
prints 
```
sacred.river.alph 
caves[0]ice 
caves[1]ice 
```