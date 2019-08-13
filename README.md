# consol-app-C++
console app that fetches the ip-number from the Simple Public IP Address API, the app supported by cmake and make , C++.

This project and C++ Requests both use CMake.

When cloning, you need to clone recursively to get the contents of all submodules :
git clone --recursive

Then make a build directory and do a typical CMake build from there:
mkdir build
cd build
cmake ..
make

This should produce a binary in the build directory called example,run it and you will get json response in the terminal.
to be able to run the executable file you need gcc installed , 

an example of how to run the executable : 
./example 
