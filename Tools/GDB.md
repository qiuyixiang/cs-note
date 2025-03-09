
# Command

# run

If you want to run gdb on the executable just type
```shell
gdb [executable-name]
```


| Command            | Usage                                             |
| ------------------ | ------------------------------------------------- |
| r [arg1] [arg2]... | Run the program using arguments [arg1], [arg2]... |


## breakpoint

Set a breakpoint in gdb, using [b/break]

| Command     | Usage                              |
| ----------- | ---------------------------------- |
| b FUNCTION  | Set breakpoint at function         |
| b FILE:LINE | Set breakpoint at line in the file |
|             |                                    |

## layout

You can using layout to display different source code layout


| Command      | Usage                  |
| ------------ | ---------------------- |
| layout src   | Apply source layout    |
| layout asm   | Apply assembly layout  |
| layout regs  | Apply registers layout |
| layout next  | Apply the next layout  |
| layout prev  | Apply the prev layout  |
| layout split | Apply the split latout |

## execution


| Command | Usage                                     |
| ------- | ----------------------------------------- |
| n       | Execute one line without enter a function |
| s       | Execute one line and step into a function |
| si      | Execute one line in assembly              |
| finish  | Finish execute in a function              |

## information


| Command             | Usage                                                                                                                                              |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| p [variable]        | print values                                                                                                                                       |
| x/[type] [variable] | Interpret the variable as a pointer and print the value at that location as a specific type. x/s for strings, x/d for decimal, x/x fo hexadecimal. |
| bt                  | print stack trace                                                                                                                                  |
