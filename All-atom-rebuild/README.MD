# This program is used to transfer a coarse-grained (CG) structure into its corresponding all-atom structure

The program is for CG structures involving three CG beads at P, C4’, and N1 atom for pyrimidine (or N9 atoms for purine).

```
# Compilation and usage under linux

gcc -Wall rebuild.c -o rebuild -lm

# Run in the example dir

./rebuild

# Output:
   
#  All_atom.pdb

An example is:
```
gcc -Wall rebuild.c -o rebuild -lm
./rebuild
Sequence:GGCGCAGUGGGCUAGCGCCACUCAAAGGCCCG
Secondary structure:(((((...[[[[[.))))).......]]]]].
Rebuilding completed!
File name: All_atom.pdb
Note: the subfolder "fragment/" and compiled "rebuild" should be in the same folder.
Please feel free to contact us if you have any question! zjtan@whu.edu.cn
