####stm32相关
######include path问题
1. c_cpp_properties.json里添加include path
2. 同上添加defines,参考.mxproject中的CDefines
    * USE_HAL_DRIVER
    * STM32F407xx
3. cStander: C99
4. compilerPath:
   这项在IDE里面找
5.多个.c时若要运行需要改task.json中的args