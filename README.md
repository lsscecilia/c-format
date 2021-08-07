# Basic format for C++ program

## basic commands 



### To build & compile

#### 3 ways to do it

``` bash 
cd build
cmake -DCMAKE_BUILD_TYPE=Release .. && make
```

``` bash
cd build && make
```

``` bash
cmake -H. -Bbuild

cmake --build build -- -j3
```

### Run the program

```bash
./build/bin/project 
./build/bin/project_test
```