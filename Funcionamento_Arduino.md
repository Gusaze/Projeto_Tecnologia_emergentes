1 -Cartão RFID + Leitor RC522:
Colaborador aproxima o cartão RFID ao leitor.
O Arduino lê o código do cartão e verifica se ele é autorizado.
2 - Arduino:
Faz a leitura do cartão, valida, liga relé, aciona o LED e captura localização GPS.
3- Relé:
Simula o acionamento da ignição do carro.
4- LED Verde:
Liberado, carro ligado.
5- LED Vermelho:
Negado, cartão não autorizado.
6- Módulo GPS:
Quando o cartão é autorizado, o GPS envia a localização para a central
