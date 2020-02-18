## Table 1. The move (```mv```) command

```mv``` [From (file or directory)] [To (file or directory)] (with no extra options)


|         | <img width=150/> To existing file <img width=125/>  | <img width=150/> To new file <img width=200/> | To existing directory                             | To new directory                                                     |
|-----------------|--------------------------------------------------|--------------|-------------------------------------------------------------------|------------------------------------------------------------------------|
| From: File       | __Overwrite!__ Content of existing file will be lost | Rename file  | Move to directory                                                 | Not possible: first, you need to create the directory with ```mkdir``` |
| From: Directory | Not possible                                     | Not possible | The "From" directory becomes a subdirectory of the "To" directory | Rename directory                                                       |
