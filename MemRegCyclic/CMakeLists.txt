cmake_minimum_required(VERSION 3.19.2)

project(MemRegCyclic)

set(SOURCES
    ./main.c

    )

#find_package(SimpleITK)
add_executable ( memregcyclic ${SOURCES} )
#target_link_libraries ( sitk_example ${SimpleITK_LIBRARIES} )
