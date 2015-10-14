Red-Black Tree
==============

C implementation of Red-Black Trees (https://en.wikipedia.org/wiki/Red%E2%80%93black_tree).

Build and test
--------------

Build the library only:
```
cmake .
make
```
or
```
cmake -DCMAKE_BUILD_TYPE=Release .
```

Build with tests:
```
cmake -DCMAKE_BUILD_TYPE=Debug .
make
```

Run tests:
```
make test [ARGS="-V"]
```

