# Ex21_UART

O programa tem as seguintes funções:

1. Configura a UART0 do TM4C1294 para taxa de transmissão de 300 bps, 8 bits de dados, paridade par e 2 stop bits
2. Aguarde a recepção do caracter ‘\r’ pela UART0
3. Após a recepção do caracter ‘\r’, responda transmistindo a mensagem “Sistemas Microcontrolados\r\n” pela UART0
