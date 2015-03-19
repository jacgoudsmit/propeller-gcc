# propeller-gcc
A port of GCC to the Parallax Propeller

This project uses submodules so it requires a slightly different setup procedure:

    git clone https://github.com/dbetz/propeller-gcc.git
    cd propeller-gcc
    git submodule init
    git submodule update

After cloning the propeller-gcc repository and updating the submodules you need to
fetch some additional libraries needed to build GCC. Doing this requires that you
have wget available on your machine.

    cd propeller-gcc/gcc
    ./contrib/download_prerequisites
