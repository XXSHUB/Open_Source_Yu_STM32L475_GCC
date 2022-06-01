# Open_Source_Yu_STM32L475_GCC
# 一、环境介绍
+ 系统：Window10 LTSC  
+ [STM32CubeMX](https://www.st.com/zh/development-tools/stm32cubemx.html)：图形化的界面，配置基于HAL库的初始化代码  
+ [VScode](https://code.visualstudio.com/)：集成开发环境IDE  
+ [MakeFIle Tool](https://marketplace.visualstudio.com/items?itemName=ms-vscode.makefile-tools/)：为 Makefile 项目提供 IntelliSense 配置  
+ [Cortex-Debug](https://marketplace.visualstudio.com/items?itemName=marus25.cortex-debug/)：为ARM Cortex-M 微控制器的调试提供支持  
+ [Mingw-w64](https://sourceforge.net/projects/mingw-w64/files/mingw-w64/mingw-w64-release/)：C/C++编译器（Minimalist GNU on Windows）提供make指令,编译本机程序  
+ [gcc-arm-none-eabi](https://developer.arm.com/downloads/-/gnu-rm/)：GCC交叉工具链，编译ARM指令集程序,包括编译器(gcc)，调试器(gdb），链接器(ld)  
+ [OpenOCD](https://gnutoolchains.com/arm-eabi/openocd/)：调试器(Open On-Chip Debugger)  
开发板：潘多拉 STM32L475
# 二、功能介绍
GCC开源编译环境下的例程测试
# 三、调用函数
>HAL_UART_Receive_IT()
