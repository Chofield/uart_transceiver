# uart_transceiver

1. uart_top.v:  top file of the uart transceiver
                      including clk, reset, 1-bit received input and 10-bits transmitted output (1-bit start bit + 7-bits data + 1-bit parity + 1-bit stop bit)

2. uart_mcu  :  control section to do rx-tx-rx-tx loop

3. uart_para :  general parameter

4. uart_rx   :  receiver section

5. uart_tx   :  transmission section
