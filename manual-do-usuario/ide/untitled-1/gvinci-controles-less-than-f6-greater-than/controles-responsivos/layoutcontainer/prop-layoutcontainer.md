---
description: Propriedades
---

# Prop: LayoutContainer

![](../../../../../../.gitbook/assets/image%20%2895%29.png)

## Aparência

### BackColor

Defina uma cor de fundo para o controle. Clique no extensor da propriedade e selecione entre Personalizar \(incluindo Gradiente\), Cores do sistema e Web.

### BackgroundImage

Selecione uma imagem de fundo através da galeria de imagens clicando no botão extensor da propriedade.

### BackgroundPosition

![](../../../../../../.gitbook/assets/image%20%2898%29.png)

Define o posicionamento da imagem de fundo na área interna do LayoutContainer.

None - Imagem é posicionada no 



### BackgroundRepeat

Selecione o modo que deseja que a imagem de fundo seja repetida.

![](../../../../../../.gitbook/assets/image%20%28110%29.png)

NoRepeat - Imagem aparece apenas uma vez.

Repeat - Imagem de fundo é repetida de modo a preencher todo o fundo lado a lado.

RepeatX - Imagem de fundo é repetida horizontalmente, no eixo X.

RepeatY - Imagem de fundo é repetida verticalemtne, no eixo Y.

### BackgroundSize

![](../../../../../../.gitbook/assets/image%20%28102%29.png)

### BackgroundStretch

![](../../../../../../.gitbook/assets/image%20%2894%29.png)

### ContainerType

![](../../../../../../.gitbook/assets/image%20%2888%29.png)

## Diversos

### ExtraProperties

Defina propriedades extras para o controle ASP.NET/HTML. O controle LayoutContainer é gerado como um objeto do tipo div.

```text
<div id="LayoutContainer1" class="containerDefault container-fluid c_LayoutContainer1">
```

Veja que por padrão o controle tem as propriedades "id" e "class". Usando a propriedade ExtraProperties, poderá adicionar mais propriedades que serão geradas para o objeto div correspondente ao LayoutContainer que está definindo as propriedades, obtendo uma customização de um controle padrão, conforme sua necessidade de projeto.

### ExtraStyleProperties

As propriedades extras de estilo são adicionadas no arquivo .CSS específico de cada página. Será criada uma classe com um prefixo "c\_" no arquivo .CSS do módulo em questão e acrescentado o ID do controle LayoutContainer onde estarão as definições definidas nesta propriedade.

Assim, se seu LayoutContainer se chamar "LayoutContainer1", na propriedade ID, então, no arquivo .CSS da página, existirá uma definição como abaixo:

```text
.c_LayoutContainer1
{
	border: 8px;
	background-size: auto;
	cursor: inherit;
}
```

Na propriedade ExtraStypeProperties, ao clicar no botão extensor da propriedade, é aberto o SimpleEditor. Onde irá editar a lista de propriedades e valores, no seguinte padrão:

nomepropriedade: valorpropriedade;

Caso precise definir apenas algumas poucas propriedades, poderá editar diretamente no campo da propriedade ou clique no botão extensor para que todo o texto com as definições seja aberto para edição.

## Layout

### ShowGrid

{% hint style="danger" %}
Propriedade não está em uso atualmente e pode ser retirada e futuras versões.
{% endhint %}

### VerticalAlignment

![](../../../../../../.gitbook/assets/image%20%2889%29.png)

Define o alinhamento vertical do controle LayoutContainer com relação ao Form.

A opção "Manual" determina um alinhamento livre, conforme posicionamento feito arrastando o controle com o mouse ou usando as teclas de setas de movimentação para cima ou para baixo.

A opção "Top" alinha o controle no topo do Form. A opção "Center" centraliza o controle verticalmente na região central do formulário. Enquanto que a opção "Bottom" alinha verticalmente o controle na parte inferior do Form.

### ZIndex

Define a ordem de empilhamento de objetos. Um objeto com valor maior de ZIndex estará sempre na frente de objetos com ZIndex menor.

As teclas CTRL+K e CTRL+Q levam o objeto a um maior ZIndex ou menor ZIndex, respectivamente. Fazendo com que um controle fique mais para frente ou mais para trás de outro.

O valor da propriedade pode ser editado diretamente.

Na barra de ferramentas da janela de design, os botões destacados na imagem abaixo são responsáveis por trazer um objeto para a frente dos demais ou levar o objeto para trás dos demais. Portanto, alterando o ZIndex dos mesmos:

![](../../../../../../.gitbook/assets/image%20%2896%29.png)

## Miscellaneous

### ID

Define um nome ou identificação para o controle, de modo que possa ser referenciado em código e também seja identificado de forma unívoca nos locais onde são listados. Exemplo:

![](../../../../../../.gitbook/assets/image%20%2892%29.png)

No topo do painel de propriedades são listados numa caixa de seleção todos os controles posicionados na tela. Sendo exibido do lado esquerdo o ID do controle e do lado direito o tipo do controle.

O nome do controle é de livre escolha, evitando-se o uso de palavras-chaves que corresponda a comandos das linguagens de programação envolvidas. Devem começar com letras, evitar caracteres especiais e preferencialmente usar nomes autoexplicativos que tenham significado claro para o objetivo que estão empregados no projeto.

O Gvinci gera um ID padrão para cada controle adicionado na tela de design, usando o nome do tipo de controle seguido de um valor numérico sequencial. Dessa forma, já é possível a identificação de cada controle, mas fique livre para renomeá-los como achar adequado.

## Visibility

### Display

![](../../../../../../.gitbook/assets/image%20%28104%29.png)

Define a visibilidade dos controles conforme as definições de [Display do Bootstrap](https://getbootstrap.com/docs/4.0/utilities/display/). 

Veja também:

[https://developer.mozilla.org/en-US/docs/Web/CSS/display](https://developer.mozilla.org/en-US/docs/Web/CSS/display) e [https://www.w3schools.com/cssref/pr\_class\_display.asp](https://www.w3schools.com/cssref/pr_class_display.asp)

### LoginVisibility

![](../../../../../../.gitbook/assets/image%20%28112%29.png)

Define a visibilidade do controle conforme o status da autenticação.

Always - Exibe sempre o controle.

OnlyLoggedIn - Exibe o controle apenas quando existe uma seção autenticada ativa.

OnlyLoggedOut - Exibe o controle apenas quando não existe uma seção autenticada ativa.



