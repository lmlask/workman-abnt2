# Workman-ABNT2
Layout Workman adaptado ao padrão ABNT2 de teclados brasileiros.

Desenvolvido no excelente KLFC de Aldo Gunsing (https://github.com/39aldo39/klfc).

O layout Workman (https://workmanlayout.org/) foi desenvolvido em 2010 por OJ Bucao como forma de garantir uma experiência de digitação mais confortável e potencialmente mais rápida que o terrível QWERTY, ao mesmo tempo corrigindo as falhas que encontrou no layout Colemak.

O layout original foi desenvolvido para uso no inglês e, portanto, não suporta alguns caracteres especiais do português - ¨´`^~ç - entre outros.

Esta versão implementa todos os diacríticos e caracteres especiais necessários para digitar em português, e a disposição das teclas funciona muito bem para a utilização no layout ABNT2 e no português brasileiro. Os caracteres mais comuns estão dispostos na home row, e os movimentos necessários são muito menores e mais confortáveis que num teclado QWERTY.

Os sinais ´`~^ estão em suas posições normais do ABNT2. A cedilha (Ç) foi movida para a posição P do QWERTY (;: no Workman originall).

## Extend

![extend](https://user-images.githubusercontent.com/62627597/133872830-0d0f2ca3-d08e-45bd-ae10-a13e7b7aec48.png)

Esta versão implementa uma camada de extensão ao teclado. Para acessá-la, a tecla CapsLock foi substituída por uma tecla Extend - de baixa utilização e fácil acesso, é a mais adequada para tal. 

A camada de extensão permite navegação rápida e outros atalhos úteis e/ou comuns em suas posições usuais do layout QWERTY, como recortar, copiar e colar; também disponibiliza uma tecla BACKSPACE e uma tecla ENTER que são mais facilmente acessíveis desta forma do que retirando a mão direita da posição padrão. 

Caso você digite em português e inglês, o atalho Extend+T (posição F do QWERTY) é um apóstrofe facilmente acessível para contrações e genitivos em inglês.

Utilizar a camada de extensão requer prática, assim como aprender um novo layout, mas a extensão é incrivelmente poderosa para tornar o processo de input muitas vezes mais eficiente, rápido e confortável, especialmente quando utilizado por lognos períodos.

# Instalação

## Windows
Faça download do repositório e utilize os arquivos da pasta 'Windows'.

O layout foi implementado no excelente PKL de Máté Farkas, então é completamente portátil, e pode ser utilizado em qualquer computador, mesmo sem direitos de administrador.

Basta iniciar pkl.exe e o layout estará ativo. Shift+F1 esconde a imagem de ajuda, e LAlt + RAlt desativam o layout.

## Linux
Faça download do repositório e utilize os arquivos da pasta 'Linux'.

Execute o script 'install-system.sh' para instalar o layout, se seu sistema utiliza XKB. Depois, pode selecionar e gerenciar o layout nas configurações do teclado normalmente.

Se preferir não instalar o layout ou se seu sistema não utiliza XKB, execute o script 'run-session.sh' para ativar o layout durante sua sessão atual.

O arquivo .json incluso pode ser usado pelo KLFC caso você decida compilar ou modificar o layout. Caso contrário, não é utilizado.

# Licença
GNU General Public License 3
