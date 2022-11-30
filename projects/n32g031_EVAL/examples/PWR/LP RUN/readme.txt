1������˵��
    1��LP RUNģʽ�Ľ�����˳���


2��ʹ�û���

    /* ���������������ǰ����ʹ�õ�����������Ƽ��汾�� */
    IDE���ߣ�KEIL MDK-ARM 5.21.1.0
      
    /* Ӳ�����������̶�Ӧ�Ŀ���Ӳ��ƽ̨ */
    �����壺N32G031C8L7-STB V1.0     


3��ʹ��˵��

    ϵͳ���ã�
        1��ʱ��Դ��HSE+PLL/LSE
        2��ʱ��Ƶ�ʣ�48M/4M


    ʹ�÷�����
        ��KEIL�±������¼�������壬���ӵ������ϵ���һ�ᣬ�������Ա�С���ֹ�һ������ֱ��
        ѭ���������鿴��ӡ��Ϣ���Կ���������˳�LP RUNģʽ��
            


4��ע������
    ������LP RUNģʽʱ��ϵͳʱ���л�����LSE/LSI�����˳�ʱ����Ҫ�л��û�Ĭ��ϵͳʱ��


1. Function description
    1. Entry and exit of LP RUN mode.


2. Use environment

    /* Software development environment: the name and version number of the software tool used in the current project */
    IDE tool: KEIL MDK-ARM 5.21.1.0
      
    /* Hardware environment: the development hardware platform corresponding to the project */
    Development board: N32G031C8L7-STB V1.0


3. Instructions for use

    System Configuration;
        1. Clock source: HSE+PLL/LSE
        2. Clock frequency: 48M/4M


    Instructions:
        After compiling under KEIL, it is burned to the evaluation board, and the ammeter is connected in series. After a while, the current becomes significantly smaller. After a while the current increases again.
        Cycle back and forth, check the print information to see entering and exiting the LP RUN mode.
            


4. Matters needing attention
    When entering LP RUN mode, the system clock is switched to LSE/LSI, and when exiting, it needs to switch back to the user default system clock

