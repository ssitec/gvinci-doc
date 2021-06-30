# Design

![](../../../../.gitbook/assets/image%20%28134%29.png)

O desenho das telas de um projeto no **Gvinci** é feito utilizando-se a aba "Design" do módulo em edição. 

A janela de Design tem sua barra de ferramentas própria que poderá mudar quando se tem um objeto selecionado ou múltiplos objetos selecionados e também entre módulos sem acesso a dados ou páginas de dados.

A imagem abaixo, mostra a barra de ferramentas do Design com apenas um objeto selecionado, no caso, o objeto Form1.

![Barra de ferramentas com apenas um objeto selecionado](../../../../.gitbook/assets/image%20%28128%29.png)

Com múltiplos objetos selecionados, teremos uma barra de ferramentas com mais opções, sendo mostrado o nome do último objeto que foi selecionado da múltipla seleção feita, conforma imagem abaixo:

![Barra de ferramentas com m&#xFA;ltiplos objetos selecionados](../../../../.gitbook/assets/image%20%28113%29.png)

Com múltiplos objetos selecionados são exibidas muito mais botões de funções, tendo o objeto destacado, como o objeto de referência para as ações invocadas pelo clique nos respectivos botões.

Vamos começar detalhando as funções básicas dos botões para único objeto selecionado, descrevendo a função de cada um.

![Barra de ferramentas em  P&#xE1;gina de dados](../../../../.gitbook/assets/image%20%28167%29.png)

## Grupo Auto geração

### ![](../../../../.gitbook/assets/image%20%28168%29.png) Auto geração de tela padrão

### ![](../../../../.gitbook/assets/image%20%28161%29.png) Auto geração de tela com grid

### ![](../../../../.gitbook/assets/image%20%28162%29.png) Auto geração de tela com repeater

## Grupo alterações

### ![](../../../../.gitbook/assets/image%20%28122%29.png) Desfazer

Cada vez que clicar neste botão, serão desfeitas as últimas ações de edição do desenho da tela, da mais recente para a alteração mais antiga, desde o momento que iniciou a edição do módulo.

{% hint style="info" %}
O atalho CTRL+Z pode ser usado para realizar a mesma função do clique neste botão.
{% endhint %}

### ![](../../../../.gitbook/assets/image%20%28133%29.png) Refazer

Cada vez que clicar neste botão, serão refeitas as alterações que tenham sido desfeitas pela função "Desfazer", que ocorreram desde que o módulo foi aberto para edição.

{% hint style="info" %}
O atalho CTRL+Y pode ser usado para realizar a mesma função do clique neste botão.
{% endhint %}

## Grupo Alinhamentos

### ![](../../../../.gitbook/assets/image%20%28170%29.png) Alinhar a esquerda

### ![](../../../../.gitbook/assets/image%20%28163%29.png) Alinhar ao topo

### ![](../../../../.gitbook/assets/image%20%28159%29.png) Alinhar a direita

### ![](../../../../.gitbook/assets/image%20%28160%29.png) Alinhar embaixo

## Grupo centralização \(referencial controles\)

![](../../../../.gitbook/assets/image%20%28175%29.png)

![](../../../../.gitbook/assets/image%20%28175%29.png) 

![](../../../../.gitbook/assets/image%20%28158%29.png)

## Grupo dimensionamento

![](../../../../.gitbook/assets/image%20%28164%29.png)

![](../../../../.gitbook/assets/image%20%28166%29.png)

![](../../../../.gitbook/assets/image%20%28171%29.png)

## Grupo centralização \(referencial container\)

![](../../../../.gitbook/assets/image%20%28165%29.png)

![](../../../../.gitbook/assets/image%20%28172%29.png)

## Grupo espaçamento \(referencial container\)

![](../../../../.gitbook/assets/image%20%28174%29.png)

![](../../../../.gitbook/assets/image%20%28169%29.png)

## Grupo profundidade \(Z-Index\)

### ![](../../../../.gitbook/assets/image%20%28148%29.png) Trazer para frente

### ![](../../../../.gitbook/assets/image%20%28132%29.png) Enviar para trás

## Grupo Clipboard

![](../../../../.gitbook/assets/image%20%28140%29.png)

![](../../../../.gitbook/assets/image%20%28130%29.png)

## Grupo Capitalização

### ![](../../../../.gitbook/assets/image%20%28119%29.png) Primeira letra maiúscula

Transforma a primeira letra de cada palavra do texto do controle selecionado em letra maiúscula.

![](../../../../.gitbook/assets/image%20%28180%29.png)

### ![](../../../../.gitbook/assets/image%20%28139%29.png) Letras maiúsculas

Transforma todas as letras do texto do controle selecionado em letras maiúsculas.

![](../../../../.gitbook/assets/image%20%28178%29.png)

### ![](../../../../.gitbook/assets/image%20%28123%29.png) Letras minúsculas

Transforma todas as letras do texto do controle selecionado em letras minúsculas.

![](../../../../.gitbook/assets/image%20%28177%29.png)

### ![](../../../../.gitbook/assets/image%20%28124%29.png) Mostrar TabIndex

O TabIndex é a propriedade responsável por definir a ordem com que os controles receberão o foco cada vez que for pressionada a tecla TAB ou ENTER. Ao clicar neste botão, os controles que podem receber o foco mostrarão um pequeno número no canto superior esquerdo que corresponde ao mesmo valor da propriedade TabIndex do referido controle.

![](../../../../.gitbook/assets/image%20%28176%29.png)



### ![](../../../../.gitbook/assets/image%20%28143%29.png) Bloquear edição

Quando achar que seu módulo estiver pronto, que não deve receber atualizações frequentes ou mesmo para evitar que acidentalmente faça alterações indesejadas no design, clique no botão para que sejam bloqueadas alterações. A imagem do botão será alterada para um cadeado fechado ![](../../../../.gitbook/assets/image%20%28179%29.png).

## Diversos

### ![](../../../../.gitbook/assets/image%20%28147%29.png) Gerar código fonte \(Módulo\)

Use este botão da aba Design quando desejar gerar os fontes do módulo, sem necessidade de geração completa da solução.

{% hint style="success" %}
Este recurso é muito interessante, pois mesmo que o projeto já esteja em execução para testes, a geração de um fontes de um módulo específico irá refletir automaticamente no navegador, bastando que atualize a página no browser.
{% endhint %}

{% hint style="danger" %}
Caso ocorra alteração de providers, uso de novas tabelas criadas, ou alterações correlatas,  será necessário fazer a geração completa da solução.
{% endhint %}

### ![](../../../../.gitbook/assets/image%20%28137%29.png) Exibir objetos ocultos



