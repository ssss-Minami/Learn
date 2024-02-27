####stm32相关
######include path问题
1. c_cpp_properties.json里添加include path
2. 同上添加defines,如
    * USE_HAL_DRIVER
    * STM32F407xx
3. cStander: C99
4. compilerPath:
   这项在IDE里面找