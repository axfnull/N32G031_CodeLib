1������˵��
     1��I2S ��ģʽ������������Ժ��л��� SPI ��ģʽ�������ݣ����л��� I2S ��ģʽ��������
2��ʹ�û���
     �������������KEIL MDK-ARM 5.30.0.0
     Ӳ������������N32G031CL-STB V1.0����
3��ʹ��˵��
     ϵͳ���ã�
         1��SystemClock��48MHz
         2��GPIO������ģʽ DEMO �壩I2S1: WS--PA4��CK--PA5��SD--PA7
                  ����ģʽ DEMO �壩I2S1: WS--PA4��CK--PA5��SD--PA7
     ʹ�÷�����
         1����������س���λ���У�
         2����ģʽ DEMO ��������ģʽ���Ȱ�ס��ģʽ DEMO �帴λ����Ȼ���ģʽ DEMO ��ȫ���ܣ�
              ���ɿ���ģʽ DEMO �帴λ�����鿴 TransferStatus1��TransferStatus2��TransferStatus3 ״̬Ϊ PASSED
4��ע������
     ��Ҫ���� demo ����ϣ�һ�������¼��ģʽ����һ�������¼��ģʽ�������������һ���ϵ磬����������ӵ� VCC �� GND

1. Function description
    1. After receiving data in I2S slave mode, switch to SPI slave mode to receive data, and then switch to I2S master mode to receive data
2. Use environment
    Software development environment: KEIL MDK-ARM 5.30.0.0
    Hardware Environment: Developed based on N32G031CL-STB V1.0
3. Instructions for use
    System Configuration;
        1. SystemClock��48MHz
        2. GPIO��(Master mode DEMO board) I2S1: WS--PA4, CK--PA5, SD--PA7
                 (Slave mode DEMO board)  I2S1: WS--PA4, CK--PA5, SD--PA7
    Instructions:
        1. After compiling, download the program to reset and run;
        2. The slave mode DEMO board enters the debug mode, first press and hold the master mode DEMO board reset button, then the slave mode DEMO board runs at full speed,
           then release the reset button of the master mode DEMO board, and check that the status of TransferStatus1, TransferStatus2 and TransferStatus3 is PASSED
4. Matters needing attention
    Two demo boards are required, one board to program the master mode program, one board to program the slave mode program, 
    the two boards need to be powered on together, and connect the VCC and GND of the two boards