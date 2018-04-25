# Code Monkey Packages
This repostory is intended to hold various coding projects
that will be rolled up into tarballs and served up by 
a webserver.  Those tarballs are to be used as a baseline 
for application generation.

The basic idea is this -- rather than generate each of the 
projects with some overly complicated code generator,
a basic compilable project will be created here.
  
That project will be rolled into a tarball which will
be unrolled and overlaid with customizations by
the app generator.

## supported:

The following permutations are supported:

| language   | build tool  | unit test framework   | notes                               |
|------------|-------------|-----------------------|-------------------------------------|
| C++        | automake    | n/a                   |                                     |
| C++        | CMake       | n/a                   |                                     |
| C++        | CMake       | gtest                 | gtest git repo fetched during cmake |




