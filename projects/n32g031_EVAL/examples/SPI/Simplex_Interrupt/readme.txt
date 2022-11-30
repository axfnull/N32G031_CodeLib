1������˵��
     1��SPI �����жϷ��ͺͽ�������
2��ʹ�û���
     �������������KEIL MDK-ARM 5.30.0.0
     Ӳ��������      ����N32G031CL-STB V1.0���� 
3��ʹ��˵��
     ϵͳ���ã�
         1��SystemClock��48MHz
         2��GPIO��SPI1: SCK--PA5�� MOSI--PA7
                         SPI2: SCK--PB13��MISO--PB14
         3���жϣ�SPI1 �ж���ں��� SPI1_IRQHandler��SPI2 �ж���ں��� SPI2_IRQHandler

     ʹ�÷�����
         1����������س���λ���У�
         2��SPI1 ��������Ҫ����ʱ���� SPI1_IRQHandler �жϺ������ͣ�SPI2 ��������Ҫ����ʱ���� SPI2_IRQHandler�жϺ������գ�
              ���ݴ�����ɺ󣬲鿴 TransferStatus ״̬Ϊ PASSED��
4��ע������
    �����ߡ������������豸��ΪMOSI���ţ��ڴ��豸��ΪMISO����

1. Function description
    1. SPI single-wire interrupt send and receive data
2. Use environment
    Software development environment: KEIL MDK-ARM 5.30.0.0
    Hardware Environment: Developed based on N32G031CL-STB V1.0
3. Instructions for use
    System Configuration;
        1. SystemClock��48MHz
        2. GPIO��SPI1: SCK--PA5,  MOSI--PA7
                       SPI2: SCK--PB13, MISO--PB14
        3. Interrupt: SPI1 interrupt entry function SPI1_IRQHandler, SPI2 interrupt entry function SPI2_IRQHandler
    Instructions:
        1. After compiling, download the program to reset and run;
        2. When SPI1 has data to send, it enters the SPI1_IRQHandler interrupt function to send, and when SPI2 has data to receive,
            it enters the SPI2_IRQHandler interrupt function to receive. After the data transmission is completed, check the TransferStatus status as PASSED;
4. Matters needing attention
    The "single wire" data lines are MOSI pins on the master side and MISO pins on the slave side