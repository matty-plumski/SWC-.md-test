## Table 1. The move (```mv```) command

```mv``` [From (file or directory)] [To (file or directory)] (with no extra options)


|         | To existing file <img width=250/>  | To new file &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;| To existing directory <img width=10/>                            | To new directory <img width=10/>                                                      |
|-----------------|--------------------------------------------------|--------------|-------------------------------------------------------------------|------------------------------------------------------------------------|
| From: File       | __Overwrite!__ Content of existing file will be lost | Rename file  | Move to directory                                                 | Not possible: first, you need to create the directory with ```mkdir``` |
| From: Directory | Not possible                                     | Not possible | The "From" directory becomes a subdirectory of the "To" directory | Rename directory                                                       |
