<!-- TITLE: px -->

#  **`px[?][owq] [len]`** hexdump of N bytes (o=octal, w=32bit, q=64bit)


```text
Usage: px[0afoswqWqQ][f] # Print heXadecimal
```


## **Tips**
  - > Use `px` to print memory. Example: `px 8 @ esp+4`

---

- **`px`** show hexdump
  - Screenshot

    ![Px](/uploads/small-p/px.png "Px")

- **`px/`** same as x/ in gdb (help x)
- **`px0`** 8bit hexpair list of bytes until zero byte
- **`pxa`** show annotated hexdump
  - Screenshot

    ![Pxa](/uploads/small-p/pxa.png "Pxa")

- **`pxA`** show op analysis color map
- **`pxb`** dump bits in hexdump form
- **`pxc`** show hexdump with comments
- **`pxd[124]`** signed integer dump (1 byte, 2 and 4)
- **`pxe`** emoji hexdump! :)
- **`pxf`** show hexdump of current function
- **`pxh`** show hexadecimal half-words dump (16bit)
- **`pxH`** same as above, but one per line
- **`pxi`** HexII compact binary representation
- **`pxl`** display N lines (rows) of hexdump
- **`pxo`** show octal dump
- **`pxq`** show hexadecimal quad-words dump (64bit)
- **`pxQ`** same as above, but one per line
- **`pxr[j]`** show words with references to flags and code
  > _Alternatively, consider using `afvd`_
  > _`pxr @ esp` stack analysis. This is also memory telescoping_
  - Screenshot

     **Green/Blue** is executable, **Red** is data **White** is value?

    ![Pxr](/uploads/small-p/pxr.png "Pxr")

- **`pxs`** show hexadecimal in sparse mode
- **`pxt[*.] [origin]`** show delta pointer table in r2 commands
- **`pxw`** show hexadecimal words dump (32bit)
  - Screenshot

    ![Pxw](/uploads/small-p/pxw.png "Pxw")

- **`pxW`** same as above, but one per line
  - Screenshot

    ![Px Cap W](/uploads/small-p/px-cap-w.png "Px Cap W")

- **`pxx`** show N bytes of hex-less hexdump
- **`pxX`** show N words of hex-less hexdump