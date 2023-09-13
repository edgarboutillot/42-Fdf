# Fdf

This project was completed as part of the curriculum at School 42. This project consists of graphically creating the schematic representation of raised terrain.

### Important
This project is only compatible with a **macOS** environment for the moment. indeed, the ***Makefile*** and the ***MiniLibX*** is not currently planned for other platforms.

### Goal of the project
Create a program that can take a text file formatted as follows: 
```c
0 0 0 0 0 0 0 0 0 0
0 9 0 0 0 9 9 9 0 0
0 9 0 0 0 9 9 9 0 0
0 9 9 9 0 9 0 0 0 0
0 0 0 0 0 0 0 0 0 0
```
To return its 3D representation of an isometric view in a graphics window at *1920x1080*.

### Runtime Arguments
The program compiled with the Makefile is called **fdf**.
When you run it through a command line call, you can pass it *an argument*.
This must be **the path of a map** you want it to represent.

Like this for example:
```shell
> ./fdf test_maps/42.fdf
```

## Credits

This project was completed by Edgar Boutillot as part of the curriculum at School 42.
