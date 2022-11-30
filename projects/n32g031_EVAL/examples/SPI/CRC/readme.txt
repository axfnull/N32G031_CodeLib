1������˵��
     1��SPI ���ͽ������ݽ��� CRC У��
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
          2��SPI1��SPI2 ͬʱ�շ����ݣ�������ɺ󣬷��� CRC ���ݣ�������ݺ� CRC ֵ��
               �鿴 TransferStatus1 �� TransferStatus2 ״̬Ϊ PASSED���ٲ鿴 CRC ֵ��
4��ע������
     ��

1. Function description
    1. SPI sends and receives data for CRC check
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
        2. SPI1, SPI2 send and receive data at the same time, after the transmission is completed, send CRC data, check the data and CRC value,
           Check that the status of TransferStatus1 and TransferStatus2 is PASSED, and then check the CRC value;
4. Matters needing attention
    No