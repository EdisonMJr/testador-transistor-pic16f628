
# Testador de Transistor com PIC16F628 ou PIC16F648

Este projeto apresenta um circuito simples que identifica automaticamente
os pinos de um transistor BJT (base, coletor e emissor) e de MOSFETS (gate, dreno e source).

Explicação detalhada no youtube:
https://youtu.be/tWX5zOY86xA?si=tbZzEYXgTQs7fTBx

## Componentes utilizados
6 Resistores de 330ohm

3 Resistores de 1kohm

1 Resistor de 10kohm

3 Resistores de 100kohm

1 Regulador	LM78L05

1 Soquete Dip 18 pinos fino para o PIC

1 PIC16F628 ou PIC16F648 (qualquer um deles serve)

3	LEDs 5mm(vermelho)

2 LEDs 5mm(verde)

1	LED 5mm(amarelo)
	
2 Lampadas arrozinho (proteção)

1 Soquete barra 3x1

1 Soquete torneado 3x1

1 Conector de bateria 9V

## Funcionamento
O microcontrolador aplica sinais de teste aos terminais do transistor
e identifica a base, o coletor e o emissor, indicando o resultado através de LEDs.

Os LEDs vermelhos indicam a pinagem:

Base (ou gate no caso de Mosfet) - Led que pisca

Coletor (ou dreno no caso de Mosfet) - Led aceso

Emissor (ou source no caso de Mosfet) - Led apagado


Os LEDs verdes indicam se é NPN ou PNP ( Canal N ou Canal P no caso de Mosfet)

O LED amarelo indica se o transistor tem diodo interno entre o coletor e o emissor.

## Arquivos
- Arquivos Gaber do layout da placa

- PDF para imprimir em papel couchê para confeccionar a placa com ferro de passar

- Lista de componentes em .txt

- Imagens do layout em .bmp

- Foto do Circuito montado

- arquivo HEX para gravar o PIC16F628

- arquivo HEX para gravar o PIC16F648

## Observações
Projeto voltado para uso didático e de bancada. Demonstração e maiores explicações no video do youtube no canal baixaimpedancia.
https://youtu.be/tWX5zOY86xA?si=tbZzEYXgTQs7fTBx
