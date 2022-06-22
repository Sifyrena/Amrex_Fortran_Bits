# Amrex_Fortran_Bits
I do not know why I need them, or why my Apple M1 system can't generate them during compile time like the x86 one does, but they look essential enough that I don't want to lose them.

Useful for people wanting to build Amrex derivatives on an Apple Silicon machine, I suppose, especially the ones that get an error such as 

```
../../subprojects/amrex/Src/Base/AMReX_constants_mod.f90:3:7:

    3 |   use amrex_fort_module, only : amrex_real
      |       1
Fatal Error: Cannot open module file ‘amrex_fort_module.mod’ for reading at (1): No such file or directory
compilation terminated.
make: *** [tmp_build_dir/o/3d.gnu.EXE/AMReX_constants_mod.o] Error 1
```

These files were generated on an Intel Mac with gfortran-10.3
