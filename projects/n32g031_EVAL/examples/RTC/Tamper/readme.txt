1������˵��
    ͨ��PC13��������֡�



2��ʹ�û���

    /* ���������������ǰ����ʹ�õ�����������Ƽ��汾�� */
    IDE���ߣ�KEIL MDK-ARM 5.21.1.0
      
    /* Ӳ�����������̶�Ӧ�Ŀ���Ӳ��ƽ̨ */
    �����壺N32G031C8L7-STB V1.0     



3��ʹ��˵��

    ϵͳ���ã�
        1��ʱ�ӣ�LSI
        2�����ڣ�PC13
        3���������ã�
                    - ����ΪUSART1��TX��PA9  RX��PA10��:
                    - ����λ��8
                    - ֹͣλ��1
                    - ��żУ�飺��
                    - �����ʣ� 115200 


    ʹ�÷�����
        1����KEIL�±������¼�������壬�ϵ�󣬸�PC13���������PC13��GND�����ڴ�ӡ���Tamper interrupt��
                
                

4��ע������
    ��



1. Function description
    Intrusion is detected by PC13.



2. Use environment

    /* Software development environment: the name and version number of the software tool used in the current project */
    IDE tool: KEIL MDK-ARM 5.21.1.0
      
    /* Hardware environment: the development hardware platform corresponding to the project */
    Development board: N32G031C8L7-STB V1.0



3. Instructions for use

    System Configuration;
        1. Clock: LSI
        2. Detection port: PC13
        3. Serial port configuration:
                    - Serial port is USART1 (TX: PA9 RX: PA10):
                    - Data bits: 8
                    - Stop bit: 1
                    - Parity: none
                    - Baud rate: 115200


    Instructions:
        1. After compiling under KEIL, burn it to the evaluation board. After power-on, connect an external pull-up to PC13, connect PC13 to GND, and the serial port will print out Tamper interrupt.
                               

4. Matters needing attention
    none