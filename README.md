- - - EDITOR RANDÔMICO - - -
Patch para TouchDesigner - dispositivo de edição randômica de vídeo.

tutorial 0.001

O "patch" foi criado num software chamado TouchDesigner. É preciso verificar compatibilidade com sua máquina instalar o software -> https://docs.derivative.ca/index.php?title=System_Requirements

1 - Baixar e instalar. -> https://www.derivative.ca/099/Downloads/
Na momento da instalação tem uma opção de uso não-comercial, com algumas limitações mas é o suficiente pra muita coisa.


2. Abrir o arquivo/projeto random.edit.toe.


3. Importar clipes de vídeo para dentro do projeto.


4. Conectar a saída dos novos vídeo na entrada do nódulo "SWITCH". Para desconectar os nódulo basta clicar em cima da conexão com o botão direito do mouse, e no menu que abrir escolher desconectar. 


5. Ajustar os parâmetros da onda - nódulo "NOISE" - em relação com o nó "MATH" São esses parâmetros que controlam a dinâmica das transições/cortes.
Experimente os diversos tipos de onda - SPARCE, RANDOM, BROWNIAN, etc.

No nódulo "NOISE", o equilíbrio fica entre as variáveis - "TYPE", "PERIOD", e "AMPLITUDE".
No nódulo "MATH", na aba "RANGE", o número deve aumentar conforme o número de clipes de vídeo, em equilíbrio com as equalizações do NOISE.

* Comece experimentando com os vídeo que já tem dentro do projeto. Conecte os que estão faltando e aumente o RANGE para 4. Mude o tipo da onda e varie a amplitude e o período. Comece com valores pequenos.

6. Se você chegou até aqui, me fale sobre sua experiência. Posso tentar te ajudar a encontrar os ajustes finais para seu projeto.
