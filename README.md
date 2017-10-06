## Steps or configuring the toolchain on windows:
### 1. put the "tools" folder at an arbitary directory
### 2. modify the "start_gcc.bash"
1. change thest lines to specify your "tools" folder directory
- "set PATH = $(Your "tools" folder directory)\tools\gnutools\bin;"
- "set PATH = $(Your "tools" folder directory)\tools\openocd\bin;" 
- "set PATH = $(Your "tools" folder directory)\tools\GNU Tools ARM Embedded\4.9 2015q3\arm-none-eabi\bin;" 
- "set PATH = $(Your "tools" folder directory)\tools\GNU Tools ARM Embedded\4.9 2015q3\bin;" 
2.  (Optional) specify your project directory and the editor you like to use
3.  Save and quit "start_gcc.bash"
### 3. run "start_gcc.bat" **in cmd.exe**, find your project MakeFile directory and use "make -j4 all" to compile the target
