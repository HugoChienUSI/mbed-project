# NOTE: This file is generated by yotta: changes will be overwritten!

add_library(cmsis-core-stm32f4 dummy.c)

target_link_libraries(cmsis-core-stm32f4
    uvisor-lib
    cmsis-core
    mbed-hal-st-stm32f4
    cmsis-core-stm32f401xe
)

