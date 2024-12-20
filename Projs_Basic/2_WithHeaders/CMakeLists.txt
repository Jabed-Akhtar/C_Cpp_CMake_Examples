
cmake_minimum_required(VERSION 3.10)

# Project name
project (HelloWorld)

# Set source variable linking all source files to compile
set(SOURCES
    src/HelloWorld.cpp
    src/main.cpp
)

# Add source files to executable
add_executable(${PROJECT_NAME} ${SOURCES})

target_include_directories(${PROJECT_NAME}
    PRIVATE 
        ${PROJECT_SOURCE_DIR}/include
)
