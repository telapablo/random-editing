- - - EDITOR RANDÔMICO - - -
Patch para TouchDesigner - - -

tutorial 0.001

1. Baixar e instalar. 
Esse "patch" foi desenvolvido num software de programação visual chamado TouchDesigner. É preciso verificar compatibilidade com sua máquina ->   https://docs.derivative.ca/index.php?title=System_Requirements, 

baixar e instalar o software -> https://www.derivative.ca/099/Downloads/ .

No momento da instalação tem a opção de uso não-comercial. Essa versão tem algumas limitações como resolução máxima 1280x720, mas é o suficiente pra muita coisa. 


2. Baixar o zip com o arquivo do projeto. -> https://www.mediafire.com/file/182qsv1og81xo5t/random_editing.rar/file

 Na pasta dentro do arquivo zip você vai encontrar um arquivo com extensão .TOE e uma pasta com 8 vídeos. Abra o arquivo do projeto random_editing.toe que está dentro da pasta. 


3. Comece experimentando com os vídeo que já tem dentro do projeto. 

Esse exemplo está acertado com um de corte de ritmo constante. Clique no nódulo "SWITCH". Você vai perceber que o slide corre pelas 4 animações que estão conectadas. O indexador começa a contar do 0. Então quando o indicador marcar o número 2, o corte está no terceiro vídeo, quando marca 3, o corte está no quarto vídeo. Conecte os vídeos que ainda não estão conectados ao SWITCH. Você vai percerber que a onda não passa por todos os vídeos, é preciso alterar os valores da onda.

Clique em cima do nódulo "WAVE". No menu de opções, altere o valor da variável "ramp slope" de 0.03 para 0.07. Clique novamente no nódulo SWITCH e você irá perceber agora que o slide que indica a amplitude da onda passa por todos 8 os vídeos.

Você pode acrescentar mais dinâmica aos cortes conectando o nódulo "NOISE" - que se encontra abaixo do nódulo "WAVE" - ao nódulo "MATH". 

Esse é um tipo de onda mais complexo. Experimente os diversos tipos de onda - SPARSE, RANDOM, BROWNIAN, etc. Altere e ajuste os parâmetros da onda do nódulo "NOISE" com valores pequenos, fracionados. Ex: 0.5, 0.68, 0.81, 1.02 etc. No nódulo "NOISE", o equilíbrio fica entre as variáveis - "TYPE", "PERIOD", e "AMPLITUDE".

Parabéns, você está editando uma parte do Motion_Reel_PabloPablo_2019! Agora é hora de tentar com seu material.


4. Importe novos clipes de vídeo arrastando-os da pasta para dentro do projeto.


5. Conecte a saída dos novos vídeo na entrada do nódulo "SWITCH". Para desconectar os vídeos anteriores basta posicionar o mouse em cima da conexão e clicar com o botão direito do mouse e, no menu que abrir, escolher desconectar. 


6. Se você chegou até aqui, me fale sobre sua experiência. Posso tentar te ajudar a encontrar os ajustes finais para seu projeto.


+ email -> telapablo@gmail.com

+ fb -> https://www.facebook.com/pablopepreto

+ outras animações -> https://telapablo.wixsite.com/taruande
