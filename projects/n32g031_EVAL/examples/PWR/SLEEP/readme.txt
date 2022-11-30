1������˵��
    SLEEP����ͻ����˳�ʾ����


2��ʹ�û���

    /* ���������������ǰ����ʹ�õ�����������Ƽ��汾�� */
    IDE���ߣ�KEIL MDK-ARM 5.21.1.0
      
    /* Ӳ�����������̶�Ӧ�Ŀ���Ӳ��ƽ̨ */
    �����壺N32G031C8L7-STB V1.0     



3��ʹ��˵��

    ϵͳ���ã�
        1��ʱ��Դ��HSE+PLL

    ʹ�÷�����
        ��KEIL�±������¼�������壬�ϵ������ӡ��PWR_SLEEP INIT��������һ�������ӡ��Lower Power Entry������������SLEEP�ˡ�
        ����WAKEUP�����󣬴����������Lower Power Entry��������MCU����֮���ֿ�ʼ����SLEEPģʽ��


4��ע������
    ��


1. Function description
    Example of SLEEP entry and wake-up exit.


2. Use environment

    /* Software development environment: the name and version number of the software tool used in the current project */
    IDE tool: KEIL MDK-ARM 5.21.1.0
      
    /* Hardware environment: the development hardware platform corresponding to the project */
    Development board: N32G031C8L7-STB V1.0



3. Instructions for use

    System Configuration;
        1. Clock source: HSE+PLL

    Instructions:
        After compiling under KEIL and burning it to the evaluation board, the output prints "PWR_SLEEP INIT" after power-on. After a while, the output prints "Lower Power Entry", indicating that it has entered SLEEP.
        After pressing the WAKEUP button, the serial port outputs "Lower Power Entry" again, indicating that the MCU starts to enter the SLEEP mode after waking up.


4. Matters needing attention
    none
