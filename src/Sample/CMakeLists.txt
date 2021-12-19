add_library(Sample
    prime_tables.h
    sample1.h sample1.cc
    sample2.h sample2.cc
    sample3-inl.h
    sample4.h sample4.cc)

target_include_directories(Sample INTERFACE $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}>)
