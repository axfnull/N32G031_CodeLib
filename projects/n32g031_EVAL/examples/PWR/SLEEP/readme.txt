1、功能说明
    SLEEP进入和唤醒退出示例。


2、使用环境

    /* 软件开发环境：当前工程使用的软件工具名称及版本号 */
    IDE工具：KEIL MDK-ARM 5.21.1.0
      
    /* 硬件环境：工程对应的开发硬件平台 */
    开发板：N32G031CL-STB V1.0     



3、使用说明

    系统配置；
        1、时钟源：HSE+PLL

    使用方法：
        在KEIL下编译后烧录到评估板，上电输出打印“PWR_SLEEP INIT”。过了一会输出打印“Lower Power Entry”，表明进入SLEEP了。
        按下WAKEUP按键后，串口又输出“Lower Power Entry”，表明MCU唤醒之后又开始进入SLEEP模式。


4、注意事项
    无

