# Switching the build type

We will discuss the CMake options [`CMAKE_BUILD_TYPE`](https://cmake.org/cmake/help/latest/variable/CMAKE_BUILD_TYPE.html) and [`CMAKE_CONFIGURATION_TYPES`](https://cmake.org/cmake/help/latest/variable/CMAKE_CONFIGURATION_TYPES.html)
and the configurations (`Debug`, `Release`, and so forth) CMake offers.


- [example](example/)

should use `cmake -G "Visual Stuido 14 2015 Win64 -D CMAKE_CONFIGURATION_TYPES="Release;Debug" ..` instead of `cmake .. -G "Visual Stuido 14 2015 Win64 -D CMAKE_CONFIGURATION_TYPES="Release;Debug"`
