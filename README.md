# O problema 

Chuvas intensas sempre foram um grande problema nas grandes cidades, Esses eventos climáticos têm provocado enchentes, causando prejuízos materiais e o aumentando de risco epidemicos. toda essa problematizaçõa esta diretamente ligadas na segurança e integridade dos cidadaos.

<div align="center">
  <img src="https://www.rbsdirect.com.br/imagesrc/25731199.jpg?w=1024&h=512&a=c&version=1575255600" alt="Enchente" width="600"/>
  <br>
</div>
<br>

<div>O projeto de monitoramento do nível da água tem como objetivo antecipar a identificação de situações de risco relacionadas a grandes enchentes em qualquer localidade. Dessa forma, mitigando ao máximo a exposição dos cidadaos em situação de perigo, podendo ser alertado o quanto antes </div>

## Componentes:
- **Arduino Uno**
- **Protoboard**
- **Cabos Jumpers**
- **resistores( 4 X 220Ω)**
- **Leds( 1 X Vermelho, 1 X Amarelo , 1 X Verde)**
- **sensor HC-SR04**
- **Buzzer**
- **Button**

## Funcioamento:

A ideia do projeto é colocar o dispositivo em bueiros ou em lugares propensos a alagamentos, onde haverá um monitoramento com o sensor HC-SR04 medindo a distância do nível da água até o sensor, sendo possível verificar essa distância pela serial.

-**CASO 1:**

A distância entre o sensor e o nível da água é igual ou inferior a 15cm, o buzzer será ativado, o LED vermelho será aceso, e o acontecimento será armazenada na EEPROM.

-**CASO 2:**

Em situações de atenção — sendo essa a distância entre o sensor e o nível da água menor que 100cm — o LED amarelo será aceso, o buzzer não será ativado e o acontecimento não será armazenada na EEPROM.

-**CASO 3:**

Caso nenhuma dessas situações aconteça, o LED verde estará sempre acesso, indicando segurança em relação ao nível da água.

-**CASO 4:**

O button serve para o armazanameto o acontecimento independente da situação do nivel da Água.

## LINKS
link para o WOAKWI:
https://wokwi.com/projects/432710869528933377
link para o youtube:

