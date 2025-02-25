# Microprocessadores e Microcontroladores - Grupo C - Trabalho Final

## Integrantes
- 759030 - Camila Isabel de Souza Bueno
- 769170 - Davi Batista Silveira 
- 769184 - José Matheus Queiroz Rodrigues
- 769185 - Lucas Gabriel Bassan de Morais 
- 770153 -  Matheus Bolson

## Objetivo
Desenvolver um disposivo de automação através do controle de energia elétrica a qual passa em algum equipamento eletrônico, como uma lâmpada. Dessa forma, o equipamento deverá ligar e desligar de maneira remota, ou seja, esse poderá ser controlado via internet.

## Materiais utilizados
- Arduino uno;
- Ethernet Shield;
- Relé;
- Fios de energia, para conectar o aparelho na energia;
- Lâmpada com conector USB

## Breve descrição do desenvolvimento do projeto
Primeiramente será realizada a montagem das conexões entre os módulos e o Arduino da maneira como está na imagem "Montagem Ethernet.png" nesse mesmo repositório. O código utilizado para conexão e controle desses dispositivos esta salvo no arquivo "código" e ele será desenvolvido em linguagem C voltada para Arduino.

Outrossim, para realizar o controle de ligar e desligar dos dispositivos conectados será adaptado um conector de pinos macho e fêmea no qual irá correr a corrente de energia vinda da tomada e, pelo relé, será controlada a função ligar ou deligar dessa corrente.

Usando MIT App Inventor foi criado um aplicativo para controlar as funções de "liga" e "desliga" do protótipo.
O notebook em que o arduino está conectado pelo módulo ethernet deve estar na conectado no mesmo Wi-fi que o celular. 
Após feita a conexão aplicativo e arduino, o protótipo esta pronto para o uso. 


## Observações
- SEMANA 1: A ideia inicial preocupava-se apenas com o controle por meio da conexão bluetooth, logo a sugestão de controle via internet ainda não foi implementada. Por conseguinte serão estudados os materiais necessários e a maneira de integração destes com o projeto inicial no decorrer das próximas semanas. Assim, atualizações serão realizadas posteriormente na descrição do projeto. 
- SEMANA 2: Após pesquisas relacionadas ao controle do arduino via internet, foi descartada a ideia inicial de controle pelo bluetooth. Dessa forma, o "Objetivo", "Materiais utilizados" e a "Breve descrição do desenvolvimento do projeto" foram atualizados para comportarem a alteração do projeto.
- SEMANA 3: Foi feito uma conexão de ponte, entre o computador com o celular e o arduino. Para o celular foi implementado um aplicativo que tem como função ligar e desligar o objeto, no caso uma lâmpada.  
## Referências
- https://www.robocore.net/tutoriais/modulo-rele-arduino - Módulo Relé Arduino
- https://www.youtube.com/watch?v=IUVoIux3oNo&t=385s - Leitura de Sensor - App inventor Ethernet Shield
- https://www.youtube.com/watch?v=4Vc5Rmuu7kc - AppInventor y Arduino Ethernet
- https://www.youtube.com/watch?v=r15dVlsg2wA - Luminárias controladas por Arduino e Ethernet Shield via App Android
- https://www.youtube.com/watch?v=roR5kMZO2fc - Arduino Ethernet y Arduino Commander
