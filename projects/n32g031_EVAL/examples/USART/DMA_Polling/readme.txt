1������˵��

    �ò�����ʾ��USARTy��USARTz��ͨ��DMA����ѯ��ʵ�ֵĻ���ͨ�š�USARTy��
USARTz������USART1��USART2��
    ���ȣ�DMA����TxBuffer1������USARTy�������ݼĴ�����������ݷ�����
USARTz��USARTz�������ݣ�DMA��USARTz�������ݼĴ�������������RxBuffer2��
�Ƚ��ա������ݣ��ȽϽ������TransferStatus2������
    ͬʱ��DMA����TxBuffer2������USARTz�������ݼĴ�����������ݷ�����
USARTy��USARTy�������ݣ�DMA��LPUART�������ݼĴ�������������RxBuffer1��
�Ƚ��ա������ݣ��ȽϽ������TransferStatus1������   


2��ʹ�û���

    �������������KEIL MDK-ARM Professional Version 5.26.2.0

    Ӳ����������Сϵͳ��N32G031CL-STB V1.0


3��ʹ��˵��
	
    ϵͳʱ���������£�
    - ʱ��Դ = HSI + PLL
    - ϵͳʱ�� = 48MHz
    
    USART�������£�
    - ������ = 115200 baud
    - �ֳ� = 8����λ
    - 1ֹͣλ
    - У����ƽ���
    - Ӳ�������ƽ��ã�RTS��CTS�źţ�
    - �������ͷ�����ʹ��
    - DMA����ģʽ��DMA����ģʽʹ��
    
    USART�����������£�
    - USART1_Tx.PA9    <------->   USART2_Rx.PA3
    - USART1_Rx.PA10   <------->   USART2_Tx.PA2

    
    ���Բ���������
    - Demo��KEIL�����±����������MCU
    - ��λ���У����β鿴����TransferStatus1��TransferStatus2�����У�
      PASSEDΪ����ͨ����FAILEDΪ�����쳣


4��ע������