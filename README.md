# Common Platform Analysis Tools

This is a fork of a collection of tools originally used within the context of the HEP
Software Foundation (HSF). COIN-OR uses these tools (the hsf_get_platform script in particular)
primarily for naming of binary packages. 

## hsf_get_platform and hsf_platform_compatibility
These tools provide a way to derive and assemble the used platform
(architecture, operating system, compiler, build type) into the standard HSF form.
More details can be found int he corresponding HSF note.

## create_project (unused by COIN-OR)
The tool create_project creates a template CMake project. The created project
contains the standard use patterns for small CMake projects, plus support for
Doxygen and CPack. Further documentation is provided within the created
package itself inside the README.md.
