1������˵��

    �ò�����ʾ�����ʹ��USART�ദ����ģʽ��USARTy��USARTz������USART1
��USART2��
    ���ȣ��ֱ�����USARTy��USARTz�ĵ�ַΪ0x1��0x2��USARTy������USARTz
�����ַ�0x33��USARTz�յ�0x33���㷭תLED1��LED2��LED3�����š�
    һ��KEY1_INT_EXTI_LINE�߼�⵽�����أ������EXTI0�жϣ���
EXTI0_IRQHandler�жϴ�������(the ControlFlag = 0)��USARTz���뾲Ĭ
ģʽ���ھ�Ĭģʽ�У�LED����ֹͣ��ת��ֱ��KEY1_INT_EXTI_LINE�߼�⵽
������(the ControlFlag = 1)����EXTI0_IRQHandler�жϴ������У�USARTy
���͵�ַ0x102����USARTz��LED��������������ת��


2��ʹ�û���

    �������������KEIL MDK-ARM Professional Version 5.26.2.0

    Ӳ����������Сϵͳ��N32G031CL-STB V1.0


3��ʹ��˵��
	
    ϵͳʱ���������£�
    - ʱ��Դ = HSI + PLL
    - ϵͳʱ�� = 48MHz
    
    USARTy�������£�
    - ������ = 115200 baud
    - �ֳ� = 9����λ
    - 1ֹͣλ
    - У����ƽ���
    - Ӳ�������ƽ��ã�RTS��CTS�źţ�
    - �������ͷ�����ʹ��  
    
    
    USART�����������£�    
    - USART1_Tx.PA9     <------->  USART2_Rx.PA3
    - USART1_Rx.PA10   <------->   USART2_Tx.PA2    
    
    KEY1_INT_EXTI_LINE.PA6    <------->   KEY3
    
    LED1    <------->   PB1
    LED2    <------->   PB6
    LED3    <------->   PB7

    
    ���Բ���������
    - Demo��KEIL�����±����������MCU
    - ��λ���У��۲�LED1~3�Ƿ�����˸״̬
    - ������KEY���۲�LED1~3�Ƿ�ֹͣ��˸
    - �ٴΰ�����KEY���۲�LED1~3�Ƿ�ָ���˸


4��ע������