# orca_algo算法

[MetaUrban](https://github.com/metadriverse/metaurban) is A Simulation Platform for Embodied AI in Urban Spaces. orac_algo is a module to provide a reciprocal collision avoidance algorithm.

I find it cannot to build in window and throw a build exception.so i redesign build script for windows, i can build it successfully in windows.

If you have interest in it, you can try it.

# install
```
pip install ./orca_algo
```

# change log
- operators:and,or to be updated as &&,||
- #import to be updated as #include in xml_reader.h
- add "add_compile_definitions(FULL_LOG=true)" to CMakeLists.txt
- add "add_definitions(/MP)" to CMakeLists.txt