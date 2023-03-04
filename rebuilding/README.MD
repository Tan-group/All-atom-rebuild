# This program is used to transfer a coarse-grained (CG) structure into corresponding all-atom structure

CG structures involving three CG beads at P, C4’, and N1 atom for pyrimidine (or N9 atoms for purine).

```
 
# Compilation and usage under linux

gcc -Wall rebuild.c -o rebuild -lm

# Run in the example dir

./rebuild model.pdb model_AA.pdb

# Output:
   
# model_AA.pdb

An example is:
```
gcc -Wall rebuild.c -o rebuild -lm
./rebuild model.pdb model_AA.pdb
Please input secondary structure:(((((...[[[[[.))))).......]]]]].
rebuilding completed
```
Note: the subfolder "fragment/" and compiled "rebuild" should be in the same folder.
Please feel free to contact us if you have any question! zjtan@whu.edu.cn
```
