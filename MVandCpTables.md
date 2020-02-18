## Table 1. The move (```mv```) command

```mv``` From (file or directory To (file or directory)) (with no extra options)


|                 | To existing file                                 | To new file &nbsp &nbsp &nbsp &nbsp &nbsp  | To existing directory                                             | To new directory                                                       |
|-----------------|--------------------------------------------------|--------------|-------------------------------------------------------------------|------------------------------------------------------------------------|
| From: File       | Overwrite! Content of existing file will be lost | Rename file  | Move to directory                                                 | Not possible: first, you need to create the directory with ```mkdir``` |
| From: Directory | Not possible                                     | Not possible | The "From" directory becomes a subdirectory of the "To" directory | Rename directory                                                       |
