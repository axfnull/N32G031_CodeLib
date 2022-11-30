1������˵��
    1��ͨ��EXTI��������������ӡ�����


2��ʹ�û���

    /* ���������������ǰ����ʹ�õ�����������Ƽ��汾�� */
    IDE���ߣ�KEIL MDK-ARM 5.21.1.0
      
    /* Ӳ�����������̶�Ӧ�Ŀ���Ӳ��ƽ̨ */
    �����壺N32G031C8L7-STB V1.0     



3��ʹ��˵��

    ϵͳ���ã�
        1��RTCʱ��Դ��LSI
                2���ж��ߣ�EXTI_LINE7
        3���������ã�
                    - ����ΪUSART1��TX��PA9  RX��PA10��:
                    - ����λ��8
                    - ֹͣλ��1
                    - ��żУ�飺��
                    - �����ʣ� 115200 


    ʹ�÷�����
        ��KEIL�±������¼�������壬PC13���ӵ�PA7�ڣ��ϵ�󣬴���ÿ��1S���ӡһ�ζ�Ӧ����ʱ��


4��ע������
    ��



1. Function description
    1. Trigger the calendar printout through the EXTI line.


2. Use environment

    /* Software development environment: the name and version number of the software tool used in the current project */
    IDE tool: KEIL MDK-ARM 5.21.1.0
      
    /* Hardware environment: the development hardware platform corresponding to the project */
    Development board: N32G031C8L7-STB V1.0



3. Instructions for use

    System Configuration;
        1. RTC clock source: LSI
                2. Interrupt line: EXTI_LINE7
        3. Serial port configuration:
                    - Serial port is USART1 (TX: PA9 RX: PA10):
                    - Data bits: 8
                    - Stop bit: 1
                    - Parity: none
                    - Baud rate: 115200


    Instructions:
        After compiling under KEIL and burning to the evaluation board, PC13 is connected to the PA7 port. After power-on, the serial port will print the corresponding calendar time every 1S.


4. Matters needing attention
    none