1������˵��

    �ò�����ʾ��USARTy��USARTz��ʹ��Ӳ�������ƵĻ���ͨ�š�USARTy��
USARTz������USART1��USART2��
    ���ȣ�USARTy����CTS����TxBuffer1���ݣ�USARTz����RTS����
���ݣ�����RxBuffer2�����USARTz����CTS����TxBuffer2���ݣ�USARTy
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
    
    USARTy�������£�
    - ������ = 115200 baud
    - �ֳ� = 8����λ
    - 1ֹͣλ
    - У����ƽ���
    - CTSӲ��������ʹ��
    - ������ʹ��   
    
    USARTz�������£�
    - ������ = 115200 baud
    - �ֳ� = 8����λ
    - 1ֹͣλ
    - У����ƽ���
    - RTSӲ��������ʹ��
    - ������ʹ��   
    
    
    USART�����������£�    
    - USART1_Tx.PA9      <------->   USART2_Rx.PA3
    - USART1_Rx.PA10     <------->   USART2_Tx.PA2
    - USART1_CTS.PA11   <------->   USART2_RTS.PA1 
    - USART1_RTS.PA12   <------->   USART2_CTS.PA0 

    
    ���Բ���������
    - Demo��KEIL�����±����������MCU
    - ��λ���У����β鿴����TransferStatus1��TransferStatus2�����У�
      PASSEDΪ����ͨ����FAILEDΪ�����쳣


4��ע������