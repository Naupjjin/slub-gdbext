# slub-gdbext
**slub-gdbext** is a GDB extension for debugging the SLUB allocator.  
This extension is based on the `slab_caches` address and some structure offsets (Default offset for kernel 6.15.7.).  
By using these addresses, you can retrieve more information about the SLUB allocator.

## Why make this ext?
This extension works without requiring full debug symbols and supports systems with SLUB protections enabled.
