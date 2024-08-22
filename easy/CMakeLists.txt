set(EASY_SOURCES hello.cpp)

foreach(source ${EASY_SOURCES})
    string(REPLACE ".cpp" "" target_name ${source})
    add_executable(${target_name} ${source})
endforeach()
