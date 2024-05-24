add_library(rocksdb_gtest gtest-all.cc)

# Add dependency of gtest on thread library
target_link_libraries(rocksdb_gtest ${CMAKE_THREAD_LIBS_INIT})
