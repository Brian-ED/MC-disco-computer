# Minecraft disc based computer
Still very early in development and anything i say in this readme can change in the future.


# Limitations
The execution flow is made up of discs, where each isntruction is 2 discs having a total instruction set of 16.
Each instruction is a operation. operations can either take item from the , with the first one being the one currently on the stack. 
A modifier modifies the next instruction comming in.


listing of all instructions, where questionmarks mean it hasn't been chosen yet






### Operations:
```
read
write
+
- 
×
÷
=
≠ 
⌈ ceiling
⌊ floor
¨ each/map
#MAYBE: ⁼ inverse
change Type
```

### footnotes:
ceil and floor can be used for AND and NOT


# shulkerbox disc memory layout
Each disc is equivilant to half a byte inside a shulkerbox.
