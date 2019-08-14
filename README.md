# lpc_uart_server

基于LPC54018的 串口转多UART服务器



```
lpc_uart_server
├─ LPC_firmware_download_tool : Linux LPC 固件下载
├─ README.docx
├─ README.md
├─ kernel_driver ： 内核驱动
├─ misc	: 其他
├─ reference ：参考文档，一般不需要查看
└─ user_space_test_program :Linux用户空间测试脚本
```



### 串口引出功能表

| 串口      | PIN   | 复用功能 |
| --------- | ----- | -------- |
| UART0_TX  | P0_30 | 1        |
| UART0_RX  | P0_29 | 1        |
| UART0_CTS | N/A   | N/A      |
| UART0_RTS | N/A   | N/A      |
| UART1_TX  | P1_11 | 2        |
| UART1_RX  | P1_10 | 2        |
| UART1_CTS | P0_13 | 1        |
| UART1_RTS | P0_14 | 1        |
| UART2_TX  | P1_25 | 1        |
| UART2_RX  | P1_24 | 1        |
| UART2_CTS | P1_26 | 1        |
| UART2_RTS | P1_27 | 1        |
| UART3_TX  | P0_2  | 1        |
| UART3_RX  | P0_3  | 1        |
| UART3_CTS | P0_1  | 2        |
| UART3_RTS | P0_7  | 1        |
| UART4_TX  | P3_27 | 3        |
| UART4_RX  | P3_26 | 3        |
| UART4_CTS | P3_28 | 3        |
| UART4_RTS | P3_29 | 3        |
| UART5_TX  | P2_13 | 5        |
| UART5_RX  | P2_12 | 5        |
| UART5_CTS | P2_14 | 5        |
| UART5_RTS | P2_15 | 5        |
| UART6_TX  | P4_3  | 2        |
| UART6_RX  | P4_2  | 2        |
| UART6_CTS | P4_0  | 2        |
| UART6_RTS | N/A   | N/A      |
| UART7_TX  | P2_20 | 3        |
| UART7_RX  | P2_19 | 3        |
| UART7_CTS | P1_21 | 1        |
| UART7_RTS | P1_20 | 1        |
| UART8_TX  | P3_17 | 1        |
| UART8_RX  | P3_16 | 1        |
| UART8_CTS | P3_4  | 3        |
| UART8_RTS | P3_5  | 3        |
| UART9_TX  | P3_3  | 2        |
| UART9_RX  | P3_2  | 2        |
| UART9_CTS | P3_30 | 1        |
| UART9_RTS | P3_31 | 1        |

**UART0 留作debug使用，请使用UART1-UART9**