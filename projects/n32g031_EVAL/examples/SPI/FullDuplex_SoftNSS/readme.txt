1������˵��
    1��SPI ȫ˫����� NSS ģʽ���ͽ�������
2��ʹ�û���
     �������������KEIL MDK-ARM 5.30.0.0
     Ӳ��������      ����N32G031CL-STB V1.0����
3��ʹ��˵��
     ϵͳ���ã�
         1��SystemClock��48MHz
         2��GPIO��SPI1: SCK--PA5�� MISO--PA6�� MOSI--PA7
                         SPI2: SCK--PB13��MISO--PB14��MOSI--PB15
     ʹ�÷�����
        1����������س���λ���У�
        2��SPI1 ��ʼ��Ϊ�������������ݣ�SPI2 ��ʼ��Ϊ�ӻ����������� ��������ɺ󣬼�����ݣ��鿴 TransferStatus1 �� TransferStatus2 ״̬Ϊ PASSED��
             SPI2 ��ʼ��Ϊ�������������ݣ�SPI1 ��ʼ��Ϊ�ӻ����������� ��������ɺ󣬼�����ݣ��鿴 TransferStatus3 �� TransferStatus4 ״̬Ϊ PASSED��
4��ע������
     ��

1. Function description
    1. SPI full duplex software NSS mode to send and receive data
2. Use environment
    Software development environment: KEIL MDK-ARM 5.30.0.0
    Hardware Environment: Developed based on N32G031CL-STB V1.0
3. Instructions for use
    System Configuration;
        1. SystemClock��48MHz
        2. GPIO��SPI1: SCK--PA5,   MISO--PA6,  MOSI--PA7
                       SPI2: SCK--PB13, MISO--PB14, MOSI--PB15
    Instructions:
        1. After compiling, download the program to reset and run;
        2. SPI1 is initialized as a master, sending data, SPI2 is initialized as a slave, receiving data, after the transmission is completed, 
           check the data, and check that the status of TransferStatus1 and TransferStatus2 is PASSED��
           SPI2 is initialized as a master, sending data, SPI1 is initialized as a slave, receiving data, after the transmission is completed, 
           check the data, and check that the status of TransferStatus3 and TransferStatus4 is PASSED;
4. Matters needing attention
    No