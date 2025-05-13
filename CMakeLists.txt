cmake_minimum_required(VERSION 3.10)
project(DesignPattern)

set(CMAKE_CXX_STANDARD 17)


# Include the module
include(${CMAKE_SOURCE_DIR}/BuildExamples.cmake)

# Define your examples
set(EXAMPLES
        # Creational Design Patterns
        1_Factory_Method

)



# Build them
buildExamples()

