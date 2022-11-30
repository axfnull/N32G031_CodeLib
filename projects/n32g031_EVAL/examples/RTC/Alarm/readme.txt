1������˵��
    1��ͨ���趨����ʱ�������������жϡ�
    2��ͨ�����ӱ�־λ������IO���

2��ʹ�û���

    /* ���������������ǰ����ʹ�õ�����������Ƽ��汾�� */
    IDE���ߣ�KEIL MDK-ARM 5.21.1.0
      
    /* Ӳ�����������̶�Ӧ�Ŀ���Ӳ��ƽ̨ */
    �����壺N32G031C8L7-STB V1.0     



3��ʹ��˵��

    ϵͳ���ã�
        1��RTCʱ��Դ��LSI
        2���������ã�
                    - ����ΪUSART1��TX��PA9  RX��PA10��:
                    - ����λ��8
                    - ֹͣλ��1
                    - ��żУ�飺��
                    - �����ʣ� 115200 


    ʹ�÷�����
        ��KEIL�±������¼�������壬�ϵ磬���ڰ��������趨ʱ����д�ӡ�����

4��ע������
    ��


1. Function description
    1. Trigger the alarm interrupt by setting the alarm time.
    2. Configure the IO output through the alarm flag bit

2. Use environment

    /* Software development environment: the name and version number of the software tool used in the current project */
    IDE tool: KEIL MDK-ARM 5.21.1.0
      
    /* Hardware environment: the development hardware platform corresponding to the project */
    Development board: N32G031C8L7-STB V1.0



3. Instructions for use

    System Configuration;
        1. RTC clock source: LSI
        2. Serial port configuration:
                    - Serial port is USART1 (TX: PA9 RX: PA10):
                    - Data bits: 8
                    - Stop bit: 1
                    - Parity: none
                    - Baud rate: 115200


    Instructions:
        After compiling under KEIL, burn it to the evaluation board, power on, and the serial port will print out the time set by the alarm clock.

4. Matters needing attention
    none