1������˵��

    /* ���������̹��� */
    ����������ò���ʾ���ò�ͬ��ϵͳʱ�ӣ�����MCO��PA8�������


2��ʹ�û���

    /* ���������������ǰ����ʹ�õ�����������Ƽ��汾�� */
    IDE���ߣ�KEIL MDK-ARM 5.21.1.0
      
    /* Ӳ�����������̶�Ӧ�Ŀ���Ӳ��ƽ̨ */
    �����壺N32G031C8L7-STB V1.0     

        

3��ʹ��˵��

    /* �������ģ�����÷���������:ʱ�ӣ�I/O�� */
    USART��TX - PA9��������115200
    GPIO��PA8 - ����ΪMC0ʱ�����

    /* ����Demo�Ĳ��Բ�������� */
    1.��������س���λ���У�
    2.�ֱ�����ϵͳʱ��ΪHSI��HSE��PLL���ֱ�ʹ�ô��ڴ�ӡ����ǰSYSCLK��HCLK��PCLK1��PCLK2����Ϣ�����ҿ���ʹ��PA8�����������ʱ�ӣ���ʾ�����鿴��


4��ע������

1. Function description

     /* Briefly describe the engineering function */
     This example configures and demonstrates the setting of different system clocks, and uses MCO to output from PA8


2. Use environment

     /* Software development environment: the name and version number of the software tool used in the current project */
     IDE tool: KEIL MDK-ARM 5.21.1.0
      
     /* Hardware environment: development hardware platform corresponding to the project */
     Development board: N32G031C8L7-STB V1.0

3. Instructions for use

     /* Describe the configuration method of related modules; for example: clock, I/O, etc. */
     USART: TX-PA9, baud rate 115200
     GPIO: PA8-multiplexed as MC0 clock output

     /* Describe the test steps and phenomena of Demo */
     1. After compiling, download the program to reset and run;
     2. Configure the system clock as HSI, HSE, and PLL respectively, and use the serial port to print out the current SYSCLK, HCLK, PCLK1, PCLK2 and other information, and use the PA8 multiplex pin to output the clock and view it with an oscilloscope;


4. Attention
    None