add_library(tree STATIC tree.cpp bsptree.cpp)
target_link_libraries(tree agulib ${OpenCV_LIBS})
target_include_directories(tree PRIVATE "../lib")
