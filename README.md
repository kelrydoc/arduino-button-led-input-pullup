# Projeto Arduino – LED controlado por botão

## 📌 Descrição
Projeto de sistemas embarcados utilizando Arduino Uno, onde um LED é controlado
por meio de um botão utilizando entrada digital com INPUT_PULLUP.
O projeto demonstra a leitura de entradas digitais e o controle de saídas,
além da interação entre hardware e software.

## 🛠️ Componentes utilizados
- Arduino Uno
- Protoboard
- LED
- Resistor 220Ω
- Botão (push button)
- Jumpers

## 🔌 Ligações
- Pino digital 13 → perna longa do LED  
- Perna curta do LED → resistor → GND  
- Pino digital 2 → botão  
- Botão → GND  

> O botão foi configurado com INPUT_PULLUP, dispensando o uso de resistor externo.

## 💻 Funcionamento
Quando o botão é pressionado, o pino de entrada é levado ao nível LOW,
fazendo com que o LED acenda. Ao soltar o botão, o LED apaga.

## 🚀 Aprendizados
- Leitura de entrada digital
- Uso do modo INPUT_PULLUP
- Controle de LED com botão
- Montagem de circuito em protoboard
- Depuração de erros de hardware

## 🔗 Testes
Projeto testado em ambiente de simulação (Tinkercad).
