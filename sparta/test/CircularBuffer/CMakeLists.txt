project(CircularBuffer_test)

sparta_add_test_executable(CircularBuffer_test CircularBuffer_test.cpp)

include(../TestingMacros.cmake)

sparta_test(CircularBuffer_test CircularBuffer_test_RUN)
