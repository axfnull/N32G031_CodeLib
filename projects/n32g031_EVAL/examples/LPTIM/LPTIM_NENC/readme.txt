﻿1、功能说明
    1、LPTIM 计数IN1 IN2非正交编码的下升沿个数
2、使用环境
    软件开发环境：  KEIL MDK-ARM V5.30.0.0
    硬件环境：      基于N32G031CL-STB V1.0开发
3、使用说明
    系统配置；
        1、时钟源：
                    HSE=8M,PLL=48M,AHB=48M,APB1=48M,APB2=48M,LPTIM CLK=LSI
        2、端口配置：
                    PA0选择为LPIME IN1输入
                    PA1选择为LPIME IN2输入
                    PB0选择为IO输出
                    PB1选择为IO输出
        3、LPTIM：
                    LPTIM非正交编码器模式，利用内部LSI时钟连续计数IN1 IN2下升沿个数
    使用方法：
        1、编译后打开调试模式，连接PB0和PA0，PB1和PA1，将变量NencCNT添加到watch窗口
        2、程序运行后，PB0 PB1输出20个脉冲周期，NencCNT等于20
4、注意事项
    无


1. Function description
    1. LPTIM counts the number of falling edges of IN1 IN2 non-orthogonal coding
2. Use environment
     Software development environment: KEIL MDK-ARM V5.30.0.0
     Hardware environment: N32G031CL-STB V1.0
3. Instructions for use
     System Configuration;
         1. Clock source:
             HSE=8M,PLL=48M,AHB=48M,APB1=48M,APB2=48M,LPTIM CLK=LSI
        2. Port configuration:
             PA0 is selected as LPIME IN1 input
             PA1 is selected as LPIME IN2 input
             PB0 is selected as IO output
             PB1 is selected as IO output
        3. LPTIM:
             LPTIM non-quadrature encoder mode, use the internal LSI clock to continuously count the number of falling edges of IN1 IN2
    Instructions:
         1. Open the debug mode after compiling, connect PB0 and PA0，PB1 and PA1，and add the variable encCNT to the watch window
         2. After the program runs, PB0 PB1 outputs 20 pulse cycles, and encCNT is equal to 20
4. Matters needing attention
     none