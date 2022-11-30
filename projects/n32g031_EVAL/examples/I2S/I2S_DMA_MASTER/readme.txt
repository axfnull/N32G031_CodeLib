1������˵��
     1��I2S ��ģʽͨ�� DMA �շ�����
2��ʹ�û���
     �������������KEIL MDK-ARM 5.30.0.0
     Ӳ��������      ����N32G031CL-STB V1.0����
3��ʹ��˵��
     ϵͳ���ã�
         1��SystemClock��48MHz
         2��GPIO������ģʽ DEMO �壩I2S1: WS--PA4��CK--PA5��SD--PA7
                         ����ģʽ DEMO �壩 I2S1: WS--PA4��CK--PA5��SD--PA7
         3��DMA��I2S1 ���Ͳ��� DMA_CH3 ͨ����I2S1 ���ղ��� DMA_CH2 ͨ����
         4����־��ӡ����ģʽ DEMO �� PA9(TX)�������ʣ�115200
     ʹ�÷�����
        1����������س���λ���У�
        2����ģʽ DEMO ��ʹ�ģʽ DEMO ��PA4,PA5,PA7���Ӻú���ģʽ DEMO �����Ӵ��ڴ�ӡ���ߣ��ϵ磬
             �Ȱ�ס��ģʽ DEMO �帴λ�����ɣ��ٰ��´�ģʽ DEMO ��ĸ�λ������ģʽ DEMO �������������ɿ���ģʽ DEMO ��ĸ�λ�����鿴��ӡ���Գɹ���
4��ע������
     ��Ҫ���� demo ����ϣ�һ�������¼��ģʽ����һ�������¼��ģʽ��������������ӵ� VCC �� GND

1. Function description
    1. I2S master mode sends and receives data through DMA
2. Use environment
    Software development environment: KEIL MDK-ARM 5.30.0.0
    Hardware Environment: Developed based on N32G031CL-STB V1.0
3. Instructions for use
    System Configuration;
        1. SystemClock��48MHz
        2. GPIO��(Master mode DEMO board) I2S1: WS--PA4, CK--PA5, SD--PA7
                       (Slave mode DEMO board)    I2S1: WS--PA4, CK--PA5, SD--PA7
        3. DMA: I2S1 transmission adopts DMA_CH3 channel, I2S1 reception adopts DMA_CH2 channel;
        4. Log print: master mode DEMO board PA9(TX), baud rate: 115200
    Instructions:
        1. After compiling, download the program to reset and run;
        2. After the master mode DEMO board and slave mode DEMO board PA4, PA5, PA7 are connected, 
           the master mode DEMO board is connected to the serial port printing tool, power on, 
           first press and hold the master mode DEMO board reset button, and then press the slave mode DEMO board reset button, 
           after the slave mode DEMO board has run, release the reset button of the master mode DEMO board and then check the printing test is successful;
4. Matters needing attention
    Two demo boards are required, one board to burn the master mode program, one board to burn the slave mode program, connect the VCC and GND of the two boards