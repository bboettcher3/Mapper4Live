# Mapper4Live: A Max for Live plugin to connect distributed devices and signals to Ableton Live parameters

## Installation

After cloning or downloading the repository, you'll need to build the libmapper max externals in the mapper-max-pd directory by following the instructions here: https://github.com/malloch/mapper-max-pd

Once the externals are built, open Max->Options->File Preferences and add the directory where the externals are built (mapper-max-pd/build/Debug by default).

Finally, copy the libmapper, liblo, and zlib dll files from the mapper-max-pd/build/libmapper/libmapper-main/<dll location> to your root Max folder (e.g., C:\Program Files\Cycling '74\Max 8 for Windows). See below for the default dll locations:
  
libmapper dll: build/Debug/
  
liblo dll: liblo/cmake/build/Debug/
  
zlib dll: zlib/msvc2017_64/lib/zlib/

Now you should be able to open Mapper4Live.amxd in Ableton Live similar to other M4L plugins.
