cmake_minimum_required(VERSION 3.6)
project(linux_kernel_expirement)

set(CMAKE_CXX_STANDARD 11)
#
#notifier_chain/test_chain_0.c
#notifier_chain/test_chain_1.c
#notifier_chain/test_chain_2.c
#include_directories(notifier_chain)
set(SOURCE_FILES
        helloworld.c)


add_executable(linux_kernel_expirement ${SOURCE_FILES})