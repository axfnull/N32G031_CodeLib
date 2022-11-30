1������˵��
    ������չʾ������ģ����÷���
    
2��ʹ�û���

    �������������KEIL MDK-ARM 5.26
    Ӳ��������       N32G031C8L7-STB V1.0

3��ʹ��˵��
    1��ʱ��Դ��HSE+PLL
    2����ʱ�ӣ�48MHz
    3������˿ڣ�
	   PA6		AF_PP
	   PA7		AF_PP

    4�����Բ���������
       a���������ش��븴λ����
       b����ʾ�����鿴���Σ���֤���
	
4��ע������
    1��PA6��PA7�Ĳ��λ���
    2��֧�ֽ���LPRUNģʽ����ʱ���Ƶ��Ϊpclk1��4��Ƶֵ
    3��APBʱ��Ƶ��ѡ��Ĵ���λ��freq_sel����ֵ������Ƶ��������������β�����ʧ���Ч��

1. Function description
    This example shows the usage of the buzzer module.
    
2. Use environment
    Software  environment: KEIL MDK-ARM 5.26
    Hardware environment: N32G031C8L7-STB V1.0

3. Instructions for use
     1. Clock source: HSE+PLL
     2. Main clock: 48MHz
     3. Output port��
        PA6		AF_PP
        PA7		AF_PP

     4. Test steps and phenomenon
        a. Compile and download the code to reset and run.
        b. View the waveform with an oscilloscope to verify the results.

4. Matters needing attention
     1. The waveforms of PA6 and PA7 are complementary.
     2. Support entering LPRUN mode, the output frequency is the 4 frequency division value of pclk1 at this time.
     3. The value of the APB clock frequency selection register bit (freq_sel) is determined according to the main frequency, 
        so that the output waveform will not be distorted.