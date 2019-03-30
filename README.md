- - - EDITOR RANDÔMICO - - -
Patch para TouchDesigner - - -

tutorial 0.001

1 - Baixar e instalar. 
O "patch" foi criado num software chamado TouchDesigner. É preciso verificar compatibilidade com sua máquina ->   https://docs.derivative.ca/index.php?title=System_Requirements

baixar e instalar o software -> https://www.derivative.ca/099/Downloads/

No momento da instalação tem a opção de uso não-comercial. Tem algumas limitações (como resolução máxima 1280x720), mas é o suficiente pra muita coisa. 


2. Abra o arquivo do projeto random_editing.toe que está dentro da pasta. 


3. Comece experimentando com os vídeo que já tem dentro do projeto. Dentro da pasta têm 8 animações minhas.

É um exemplo de corte com ritmo constante. Clique no nódulo "SWITCH". Você vai perceber que o slide corre pelas 4 animações que estão conectadas. Conecte os vídeos que ainda não estão conectados ao SWITCH. A onda não passa por todos os vídeos, é preciso alterar os valores da onda.

Clique em cima do nódulo "WAVE", e irá abrir um menu com opções. Altere a amplitude para 0.7 e o ramp slope 0.05. Clique novamente no nódulo SWITCH e você irá perceber que agora que o slide (que marca a amplitude da onda) passa por todos os vídeos (8).

Você pode acrescentar mais dinâmica aos cortes conectando o nódulo "NOISE" (se encontra abaixo do nódulo "WAVE") ao nódulo "MATH". 

Altere e ajuste os parâmetros da onda - nódulo "NOISE". Experimente os diversos tipos de onda - SPARCE, RANDOM, BROWNIAN, etc.

* No nódulo "NOISE", o equilíbrio fica entre as variáveis - "TYPE", "PERIOD", e "AMPLITUDE".

Comece com valores pequenos, fracionados. Ex: 0.5, 0.68, 0.81, 1.02 etc.

Parabéns, você está editando um Motion_Reel_PabloPablo_2019! Agora é hora de tentar com seu material.


4. Importe novos clipes de vídeo arrastando-os da pasta para dentro do projeto.


5. Conecte a saída dos novos vídeo na entrada do nódulo "SWITCH". Para desconectar os vídeos anteriores basta posicionar o mouse em cima da conexão e clicar com o botão direito do mouse e, no menu que abrir, escolher desconectar. Faça os ajustes conforme indicado no ítem 3.

6. Se você chegou até aqui, me fale sobre sua experiência. Posso tentar te ajudar a encontrar os ajustes finais para seu projeto.
email -> telapablo@gmail.com

fb -> https://www.facebook.com/pablopepreto
