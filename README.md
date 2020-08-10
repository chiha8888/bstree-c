# Binary Search Tree in C.

This repo demos a naive (not balanced)  binary search tree in C.

## Warning

For demo only. DON'T USE IT ON PRODUCTION ENVIRONMENT.

## Copyright

Copyright (c) 2019 Michael Chen. Licensed under MIT.

## my opinion

我覺得應該把bstree.h裡的bstree_int_t宣告給移到bstree_internal.h去，  
然後bstree.h & bstiter.h 再include "bstree_internal.h"
