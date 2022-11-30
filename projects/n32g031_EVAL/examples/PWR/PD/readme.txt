1������˵��
    1��PDģʽ�Ľ���ͻ����˳���


2��ʹ�û���

    /* ���������������ǰ����ʹ�õ�����������Ƽ��汾�� */
    IDE���ߣ�KEIL MDK-ARM 5.21.1.0
      
    /* Ӳ�����������̶�Ӧ�Ŀ���Ӳ��ƽ̨ */
    �����壺N32G031C8L7-STB V1.0     


3��ʹ��˵��

    ϵͳ���ã�
        1��ʱ��Դ��HSE+PLL
        2��ʱ��Ƶ�ʣ�48M

    ʹ�÷�����
        ��KEIL�±������¼�������壬���ӵ������ϵ���һ�ᣬ�������Ա�С������WAKEUP�����������ص���mA���𡣹���һ���ֽ���uA��
        ���������ӡ��������Կ������������Lower Power Entry�������Ѻ������PWR_PD INTI����˵��PD���Ѻ��0��ַ��ʼִ�С�
            


4��ע������
    ��


1. Function description
    1. Entry and wake-up exit of PD mode.


2. Use environment

    /* Software development environment: the name and version number of the software tool used in the current project */
    IDE tool: KEIL MDK-ARM 5.21.1.0
      
    /* Hardware environment: the development hardware platform corresponding to the project */
    Development board: N32G031C8L7-STB V1.0


3. Instructions for use

    System Configuration;
        1. Clock source: HSE+PLL
        2. Clock frequency: 48M

    Instructions:
        After compiling under KEIL, it is burned to the evaluation board, and the ammeter is connected in series. After a while, the current becomes significantly smaller. Press the WAKEUP button and the current returns to mA level. After a while it drops to uA again.
        If you turn on the print output, you can see that the serial port outputs "Lower Power Entry", and after waking up, it outputs "PWR_PD INTI", indicating that the PD starts to execute from address 0 after waking up.
            

4. Matters needing attention
    none


