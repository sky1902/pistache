set(SOURCE_FILES
    listener.cc
    net.cc
    peer.cc
)

add_library(net ${SOURCE_FILES})
include_directories (${CMAKE_CURRENT_SOURCE_DIR})

target_link_libraries(net pthread)