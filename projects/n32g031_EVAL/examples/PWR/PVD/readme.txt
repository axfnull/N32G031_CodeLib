1������˵��
    1��PVD���õ�ѹ������Ӧ���жϡ�


2��ʹ�û���

    /* ���������������ǰ����ʹ�õ�����������Ƽ��汾�� */
    IDE���ߣ�KEIL MDK-ARM 5.21.1.0
      
    /* Ӳ�����������̶�Ӧ�Ŀ���Ӳ��ƽ̨ */
    �����壺N32G031C8L7-STB V1.0     


3��ʹ��˵��

    ϵͳ���ã�
        1��ʱ��Դ��HSE+PLL

    ʹ�÷�����
        ��KEIL�±������¼�������壬ͨ���������������ģʽ����PVD_IRQHandler()�����öϵ㡣
        ȫ�����С�Ȼ���ٰѵ�ѹ����PVD���õ�ѹ��������ʱ�����ͣ�ڶϵ㴦��


4��ע������
    ��


1. Function description
    1. The PVD configuration voltage generates a corresponding interrupt.


2. Use environment

    /* Software development environment: the name and version number of the software tool used in the current project */
    IDE tool: KEIL MDK-ARM 5.21.1.0
      
    /* Hardware environment: the development hardware platform corresponding to the project */
    Development board: N32G031C8L7-STB V1.0


3. Instructions for use

    System Configuration;
        1. Clock source: HSE+PLL

    Instructions:
        After compiling under KEIL, burn it to the evaluation board, enter the debug mode through the emulator, and set a breakpoint in PVD_IRQHandler().
        Running at full speed. Then adjust the voltage to the vicinity of the PVD setting voltage, and the program will stop at the breakpoint at this time.


4. Matters needing attention
    none

