# Mapper4Live: A Max for Live plugin to connect distributed devices and signals to Ableton Live parameters

## Building

Build the libmapper max externals in the mapper-max-pd submodule directory by following the instructions here: https://github.com/malloch/mapper-max-pd

Once the externals are built, open Max->Options->File Preferences and add the directory where the externals are built (mapper-max-pd/dist by default).

If you're on Windows, you have one more step. Copy the libmapper, liblo, and zlib dll files from mapper-max-pd/build/libmapper/libmapper-2.3/dist to your root Max folder (e.g., C:\Program Files\Cycling '74\Max 8 or wherever you installed Max).

Now you should be able to open Mapper4Live.amxd in Ableton Live similar to other M4L plugins.
