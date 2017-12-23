#  `ae[aA][f] [count]`   analyse esil accesses (regs, mem..)


```text
Examples: aea show regs used in a range
```


- `aea [ops]`   Show regs used in N instructions
- `aea* [ops]`   Create mem.* flags for memory accesses
- `aeaf`   Show regs used in current function
- `aear [ops]`   Show regs read in N instructions
- `aeaw [ops]`   Show regs written in N instructions
- `aean [ops]`   Show regs not written in N instructions
- `aeaj [ops]`   Show aea output in JSON format
- `aeA [len]`   Show regs used in N bytes (subcommands are the same)