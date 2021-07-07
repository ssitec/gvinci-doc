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

As páginas de dados, após definição da propriedade "Tabela", da aba "Definitions", poderão ter geração automática de tela, clicando no botão da imagem acima.



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

Com uma visão de planos em camadas, podemos movimentar os controles para camadas mais a frente ou mais atrás na visualização. A propriedade Z-Index permite definir um valor numérico que, quanto maior, mais a frente ficará o controle.

O botão trazer para frente faz com que o controle selecionado assuma um maior valor de Z-Index para que seja exibido sobre os demais controles da tela. A cada clique, o controle vai ganhando um Z-Index maior e avançando em direção a camada mais a frente no design.

{% hint style="info" %}
Caso o controle esteja sob muitos outros de modo que não seja possível selecioná-lo através do clique do mouse, use a caixa de seleção que fica no topo do painel de Propriedades ou o painel Estrutura de objetos para selecioná-lo e em seguida, clicando no botão "Trazer para frente", até o deixar em primeiro plano se assim desejar.
{% endhint %}

### ![](../../../../.gitbook/assets/image%20%28132%29.png) Enviar para trás

Semelhante ao botão "Trazer para frente", o botão "Enviar para trás" faz com que a propriedade "Z-Index" do objeto selecionado assuma um menor valor para que seja posicionado visualmente por trás de outros controles a medida que vai sendo clicado.

## Grupo Clipboard

### ![](../../../../.gitbook/assets/image%20%28140%29.png) Copiar

Com um ou vários objetos selecionados copie-os para a área de transferência e poderá colá-los em outro módulo ou replicar os controles na mesma tela.

### ![](../../../../.gitbook/assets/image%20%28130%29.png) Colar

Após copiados para a área de transferência, os objetos poderão ser colados em outras telas ou na mesma tela de onde foram copiados por meio do botão colar.

{% hint style="success" %}
Quando colados os controles na mesma tela de onde foram copiados, os IDs dos controles recebem uma identificação acompanhada de um número sequencial de modo a não duplicar a identificação dos controles. Caso deseje, renomeie-os com identificação que facilite o referenciamento em codificação manual ou facilidade de identificação lógica de sua função.
{% endhint %}

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

{% hint style="info" %}
O atalho CTRL+SHIFT+T pode ser usado para ativar ou desativar a exibição da ordem do TabIndex nos controles pertinentes.
{% endhint %}

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

A visibilidade dos controles pode ser alterada por meio da propriedade "Display". Os controles podem ser ocultados, inclusive de forma seletiva para breakpoints específicos em layouts responsivos. O design do módulo irá refletir os efeitos das propriedades definidas, ocultando efetivamente o controle.

Através do checkbox "Exibir objetos ocultos", podemos visualisar os controles que foram ocultados, seja para executar alguma operação visual de arrastar-e-soltar, simplesmente selecionar o controle para definição de propriedades através do clique sobre o controle ou visualização de posicionamento com relação aos demais controles.

{% hint style="info" %}
Mesmo estando ocultos os controles, os mesmos podem ser selecionados através da listagem de controles na parte de acima da janela de propriedades ou através do painel "Estrutura de objetos"
{% endhint %}



