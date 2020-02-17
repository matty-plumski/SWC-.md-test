 ##Table 2. The copy (```cp```) command

```mv``` From (file or directory To (file or directory) (with no extra options):


|        | To Existing file | To New file  | To Existing directory | To New directory
------------ | ----------------- | ------------- | ---------------------- | ----------------

From:File | Overwrite! Content of existing file will be lost | Make a copy of the file | Make a copy f the file and place in the directory | Not possible: first, you need to create the directory with ```mkdir``` 
From: Directory | Not possible | Not possible | Make a copy of the "From" directory inside the "To" directory (need ```-r``` option | Make a copy of the directory (need ```-r``` option)