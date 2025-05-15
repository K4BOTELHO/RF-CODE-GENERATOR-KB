# 📡 RF Code Generator para Arduino Nano

Este projeto consiste em um **gerador de códigos RF (Radiofrequência)** desenvolvido para ser executado em um **Arduino Nano**. Ele tem como objetivo **replicar sinais de controle remoto** para programar controles virgens, sendo ideal para sistemas de automação, portões eletrônicos, alarmes e outras aplicações com transmissão RF.

---

## 🚀 Visão Geral

O sistema foi criado com base em uma lógica simples e robusta, capaz de emitir sinais RF compatíveis com controles que permitem gravação/reprodução de código. O projeto é composto por:

- Um **firmware em linguagem C** que roda no Arduino Nano.
- Uma **placa eletrônica customizada** (desenvolvida por mim), com suporte a:
  - Módulo transmissor RF 433 MHz.
  - Estabilidade e proteção para emissão contínua.

---

## 🔧 Requisitos

- Arduino Nano (ou equivalente com ATmega328P).
- Módulo RF 433 MHz transmissor.
- Resistores, placa customizada, entre outros.

---

## ⚙️ Como Funciona

1. Ao editar a logica e compilar, o Arduino emite um código RF específico a cada "X" segundos.
2. O controle virgem, colocado em modo de gravação próximo ao transmissor, **copia o sinal** emitido.
3. O LED presente no controle sinaliza que o receptor está identificando o codigo emitido pela placa (Dependendo o controle).
4. O controle agora está programado para reproduzir o código emitido.

---

## 📜 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).  
Sinta-se livre para usar, modificar e contribuir!

