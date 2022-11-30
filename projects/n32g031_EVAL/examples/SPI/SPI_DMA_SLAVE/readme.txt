1������˵��
     1��SPI ��ģʽȫ˫�� DMA ���ͺ͵��߽�������
2��ʹ�û���
     �������������KEIL MDK-ARM 5.30.0.0
     Ӳ��������      ����N32G031CL-STB V1.0����
3��ʹ��˵��
     ϵͳ���ã�
         1��SystemClock��48MHz
         2��GPIO������ģʽ DEMO �壩SPI1: SCK--PA5��MISO--PA6��MOSI--PA7
                         ����ģʽ DEMO �壩SPI1: SCK--PA5��MISO--PA6��MOSI--PA7
         3����־��ӡ����ģʽ DEMO �� PA9(TX)�������ʣ�115200
     ʹ�÷�����
         1����������س���λ���У�
         2���Ӻô��ڴ�ӡ���ߣ��ϵ磬�鿴��ӡ���Գɹ�
4��ע������
    ��Ҫ���� demo ����ϣ�һ�������¼��ģʽ����һ�������¼��ģʽ�������������һ���ϵ磬����������ӵ� VCC �� GND

1. Function description
    1. SPI slave mode full duplex DMA send and single-wire receive data
2. Use environment
    Software development environment: KEIL MDK-ARM 5.30.0.0
    Hardware Environment: Developed based on N32G031CL-STB V1.0
3. Instructions for use
    System Configuration;
        1. SystemClock��48MHz
        2. GPIO��(Master mode DEMO board) SPI1: SCK--PA5, MISO--PA6, MOSI--PA7
                       (Slave mode DEMO board)    SPI1: SCK--PA5, MISO--PA6, MOSI--PA7
        3. Log print: slave mode DEMO board PA9(TX), baud rate: 115200
    Instructions:
        1. After compiling, download the program to reset and run;
        2. Connect the serial port printing tool, power on, and check that the print test is successful;
4. Matters needing attention
    Two demo boards are required, one board to program the master mode program, one board to program the slave mode program, 
    the two boards need to be powered on together, and connect the VCC and GND of the two boards;