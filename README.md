# h5py-macos-ghrunner-mwe
An MWE for our pip3 install h5py problem on the MacOS runners.

[A minimal workflow file](.github/workflows/mwe.yml) that [fails](https://github.com/samcunliffe/h5py-macos-ghrunner-mwe/actions) because 

    error: Unable to load dependency HDF5, make sure HDF5 is installed properly
    error: dlopen(libhdf5.dylib, 0x0006): tried: 'libhdf5.dylib' (no such file), '/usr/lib/libhdf5.dylib' (no such file), '/private/var/folders/24/8k48jl6d249_n_qfxwsl6xvm0000gn/T/pip-install-0g7ro2_7/h5py_79b27cec4ed54817a7b1d51829ce2e80/libhdf5.dylib' (no such file)
