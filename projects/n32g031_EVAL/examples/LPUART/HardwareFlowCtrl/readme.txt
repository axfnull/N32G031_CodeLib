1������˵��

    �ò�����ʾ��LPUART��USARTz��ʹ��Ӳ�������ƵĻ���ͨ�š�USARTz
������USART1��
    ���ȣ�LPUART����CTS����TxBuffer1���ݣ�USARTz����RTS����
���ݣ�����RxBuffer2�����USARTz����CTS����TxBuffer2���ݣ�LPUART
����RTS�������ݣ�����RxBuffer1��
    ��󣬱ȽϽ��������뷢�����ݣ��ȽϽ���ֱ�������TransferStatus1
��TransferStatus2��


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
    - CTS��RTSӲ��������ʹ��
    - �������ͷ�����ʹ��
   
    USART�������£�
    - ������ = 115200 baud
    - �ֳ� = 8����λ
    - 1ֹͣλ
    - У����ƽ���
    - CTS��RTSӲ��������ʹ�ܣ�
    - �������ͷ�����ʹ��
    
    
    LPUART��USART�����������£�    
    - LPUART_Tx.PA1      <------->   USART1_Rx.PA10
    - LPUART_Rx.PA0      <------->   USART1_Tx.PA9
    - LPUART_CTS.PA6    <------->   USART1_RTS.PA12
    - LPUART_RTS.PA15   <------->   USART1_CTS.PA8  

    
    ���Բ���������
    - Demo��KEIL�����±����������MCU
    - ��λ���У����β鿴����TransferStatus1��TransferStatus2�����У�
      PASSEDΪ����ͨ����FAILEDΪ�����쳣


4��ע������