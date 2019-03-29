- - - EDITOR RANDÔMICO - - -
Patch para TouchDesigner - - -

tutorial 0.001

1 - Baixar e instalar. 
O "patch" foi criado num software chamado TouchDesigner. É preciso verificar compatibilidade com sua máquina ->   https://docs.derivative.ca/index.php?title=System_Requirements

e instalar o software -> https://www.derivative.ca/099/Downloads/

No momento da instalação tem uma opção de uso não-comercial. Tem algumas limitações (como resolução máxima 1280x720) mas é o suficiente pra muita coisa. 


2. Abra um dos dois arquivos/projetos random.edit.toe. que estão dentro da pasta.


3. Comece experimentando com os vídeo que já tem dentro do projeto. Dentro da pasta têm 8 animações minhas.

Altere e ajuste os parâmetros da onda - nódulo "NOISE" - em relação com o nó "MATH". São esses parâmetros que controlam a dinâmica das transições/cortes.
Experimente os diversos tipos de onda - SPARCE, RANDOM, BROWNIAN, etc.

No nódulo "NOISE", o equilíbrio fica entre as variáveis - "TYPE", "PERIOD", e "AMPLITUDE".
No nódulo "MATH", na aba "RANGE", o número deve aumentar conforme o número de clipes de vídeo, em equilíbrio com as equalizações do NOISE.

Conecte os que estão faltando e aumente o RANGE (nódulo MATH) para 6. Mude o tipo da onda (nódulo NOISE) e varie a amplitude e o período. Comece com valores pequenos, fracionados. Ex: 0.5, 0.68, 0.81, 1.02 etc.

Parabéns, você está editando um Motion_Reel_PabloPablo_2019! Agora é hora de tentar com seu material.


4. Importe novos clipes de vídeo arrastando-os da pasta para dentro do projeto.


5. Conecte a saída dos novos vídeo na entrada do nódulo "SWITCH". Para desconectar os vídeos anteriores basta posicionar o mouse em cima da conexão e clicar com o botão direito do mouse e, no menu que abrir, escolher desconectar. Faça os ajustes conforme indicado no ítem 3.


6. Se você chegou até aqui, me fale sobre sua experiência. Posso tentar te ajudar a encontrar os ajustes finais para seu projeto.
email -> telapablo@gmail.com

fb -> https://www.facebook.com/pablopepreto
