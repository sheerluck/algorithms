add_library(numbers
    gcd.cpp
    lcm.cpp
    large_integer.cpp)

CompileBenchmarkExe(gcd)
CompileTestExe(gcd)

CompileBenchmarkExe(lcm
    numbers)
CompileTestExe(lcm
    numbers)

CompileBenchmarkExe(large_integer)
CompileTestExe(large_integer)

add_subdirectory(binary)
add_subdirectory(fibonacci)
add_subdirectory(prime)
