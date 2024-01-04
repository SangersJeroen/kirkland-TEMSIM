
autostem_cuda (in directory source) uses an Nvidia graphics card (GPU) installed in
a computer. It has only been tested on a core i7 computer with Ubuntu 22.04 (Linux),
cuda toolkit 12.2 and a RTX 2080 card and on Win10 with a GTX 1050 Ti card and cuda
toolkit 12.2. Other operating systems and hardware may or may not work.  

The Win10 version (executable in win64exe directory) requires cufft64_11.dll and 
libfftw3f-3.dll to run. You may also need to install an appropriate nvida cuda driver
for your GPU.

Most Linux distributions are different enough so that programs cannot be easily
distributed in executable form and must be compiled on the machine in use. To use the
cuda based program the Nvidia cuda driver and the cuda toolkit must also be installed
(obtain separately from Nvidia) in addition to fftw etc. Then (after renaming the
file makefile.ubuntu to makefile), type "make autostem_cuda" from the command line
to compile the program before running it.

16-jul-2023