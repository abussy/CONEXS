## CONEXS Summer School

This git repository contains slides and scripts for the CONEXS summer school

### In case the program is not available

Note that the executable is compiled in order to work with as many linux systems as possible. Hence it not necessarily the most optimize one, but it should do the trick

1. Download or `git clone` this repository
2. Extract the executable from the zip archive with `unzip exec.zip`
3. Make sure you have gcc installed by running `which gcc`. If nothing appears, then type `sudo apt-get install gcc`
4. Make sure that `cp2k.sopt` is recognized as an executable by typing `chmod +x cp2k.sopt`
5. Tell the system where to find basis set and potential data by typing `export CP2K_DATA_DIR=$(pwd)"/data"`
6. Test by running `./cp2k.sopt -i test.inp -o test.out` the program should not crash and produce a test.spectrum file. The first data line of the latter should have 275.979... as excitation energy and 0.040... as oscilaltor strength


