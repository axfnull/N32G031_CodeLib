1������˵��

    �ò�����ʾ��LPUART��USARTz��ͨ��DMA���жϣ�ʵ�ֵĻ���ͨ�š�
USARTz������USART1��
    ���ȣ�DMA����TxBuffer1������LPUART�������ݼĴ�����������ɲ���
DMA�жϣ�������ݷ�����USARTz��USARTz�������ݣ�DMA��USARTz����
���ݼĴ�������������RxBuffer2����ɺ����DMA�жϡ�
    ͬʱ��DMA����TxBuffer2������USARTz�������ݼĴ�����������ɲ���
DMA�жϣ�������ݷ�����LPUART��LPUART�������ݣ�DMA��LPUART����
���ݼĴ�������������RxBuffer1����ɺ����DMA�жϡ�
    ��󣬷ֱ�Ƚ������ա������ݣ��ȽϽ������TransferStatus1����
��TransferStatus2������


2��ʹ�û���

    �������������KEIL MDK-ARM Professional Version 5.26.2.0

    Ӳ����������Сϵͳ��N32G031CL-STB V1.0


3��ʹ��˵��
	
    ϵͳʱ���������£�
    - ʱ��Դ = HSI + PLL
    - ϵͳʱ�� = 48MHz
    
    LPUART�������£�
    - ������ = 115200 baud
    - �ֳ� = 8����λ���̶���
    - 1ֹͣλ���̶���
    - У����ƽ���
    - Ӳ�������ƽ��ã�RTS��CTS�źţ�
    - �������ͷ�����ʹ��
    - DMA����ģʽ��DMA����ģʽʹ��
    
    LPUART�������£�
    - ������ = 115200 baud
    - �ֳ� = 8����λ���̶���
    - 1ֹͣλ���̶���
    - У����ƽ���
    - Ӳ�������ƽ��ã�RTS��CTS�źţ�
    - �������ͷ�����ʹ��
    - DMA����ģʽ��DMA����ģʽʹ��
    
    USART�����������£�
    - LPUART_Tx.PA1   <------->   USART1_Rx.PA10
    - LPUART_Rx.PA0   <------->   USART1_Tx.PA9

    
    ���Բ���������
    - Demo��KEIL�����±����������MCU
    - ��λ���У����β鿴����TransferStatus1��TransferStatus2�����У�
      PASSEDΪ����ͨ����FAILEDΪ�����쳣


4��ע������