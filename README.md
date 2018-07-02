# Spike

## Objetivo
O projeto elaborado tem por objetivo o monitoramento de um local, de modo que utiliza sensores de movimento para identificar qualquer tipo de movimentação fora do esperado, dispara um alarme registrando o horário na base de dados e enviando um email para o contratante.

## Componentes utilizados
- Arduino Uno
O Arduino Uno é uma placa de microcontrolador baseado no ATmega328 (datasheet). Ele tem 14 pinos de entrada/saída digital (dos quais 6 podem ser usados como saídas PWM), 6 entradas analógicas, um cristal oscilador de 16MHz, uma conexão USB, uma entrada de alimentação uma conexão ICSP e um botão de reset. Neste projeto foi utilizado um arduino uno.
- Sensores de movimento
O sensor de movimento é utilizado para detectar qualquer tipo de movimento dentro de uma distância de 7 metros do mesmo, de modo que caso afirmativo um sinal é emitido pelo sensor para o controlador. Neste projeto foram utilizados 3 sensores de movimento.
- Buzzer
O buzzer é o componente que emite som, neste projeto é utilizado para simular um alarme, de modo que ao receber um sinal proveniente do arduino, o mesmo é ligado emitindo ruídos. Neste projeto foi utilizado apenas um buzzer.
- Jumpers
São os cabos utilizados para conectar os componentes no arduino, neste projeto foram utilizados por volta de 30 jumpers.

## Reprodução
### Base de dados
A base de dados foi feita através do MySQL e consiste em tabelas que armazenam informações sobre o usuário, tais como endereço da casa, nome, email, senha e id, além dos horários em que o alarme foi acionado.
### Arduino
- Para as configurações do arduino, é somente necessário o arquivo *arduino.ino* e fazer upload no mesmo
- Conectar os sensores nas portas 2, 4 e 5 do arduino
- Conectar o buzzer na porta 3 do arduino
- Conectar os jumpers correspondentes à energia dos componentes no arduino através de uma protoboard
- Conectar os jumpers correspondentes ao fio *gnd* dos componentes no arduino através de uma protoboard
- Conectar o arduino na máquina utilizando a porta USB

### Email
### Interface web
