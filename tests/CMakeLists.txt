include_directories(${CMAKE_CURRENT_SOURCE_DIR}/..)

find_package(Check REQUIRED)
include_directories(${CHECK_INCLUDE_DIRS})

set(LIBS tree ${CHECK_LIBRARIES} m rt pthread)

add_executable(check_tree check_tree.c config.h)
target_link_libraries(check_tree ${LIBS})
