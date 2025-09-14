CÁC BƯỚC THỰC HIỆN:
1.Cấu hình GPIO:
  - PA5: Output push-pull.
  - PA9: TX.
  - PA10: RX.
<img width="1245" height="433" alt="image" src="https://github.com/user-attachments/assets/16ab1667-c100-43de-bc9a-9c004ed53000" />


2.Cấu hình USART1:
  - Baudrate = 115200.
  - Dữ liệu: 8 bit.
  - Stop bit: 1.
  - Parity: none.
  - Chế độ: Tx + Rx.

<img width="953" height="222" alt="image" src="https://github.com/user-attachments/assets/4cba06af-abff-4c73-900b-b79e1ed2c6f4" />


3. Hàm gửi dữ liệu qua USART

<img width="905" height="319" alt="image" src="https://github.com/user-attachments/assets/d0a885ad-4018-4f4d-b0d4-a3c2839391d3" />


4.Hàm delay

<img width="782" height="156" alt="image" src="https://github.com/user-attachments/assets/bd3090c7-7b8c-4e32-8cdf-3c81a6a3d4e9" />


5.Chương trình chính:

<img width="906" height="358" alt="image" src="https://github.com/user-attachments/assets/56fa4dde-e229-4c67-b6dd-716804c92ebc" />

6. Kết quả:
   -Trên terminal UART sẽ hiện "Hello from STM32!" mỗi giây.





