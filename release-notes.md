---
description: "Aqui estão os novos recursos e melhorias do Gvinci, que torna nossa ferramenta cada vez melhor. Não deixei de aproveitar! \U0001F680"
---

# Release notes

## Em Breve 🚀

Estamos animados em anunciar que estamos dando os últimos retoques em um grande novo lançamento do Gvinci, e mal podemos esperar para mostrar o que estamos construindo!

Aqui está um pouco do que está por vir:

* Uma coleção com mais de 1500 **ícones**, com possibilidade de alteração de **cores** e **tamanhos**.
* Adicionado uso do Bootstrap5;
* Gerenciador de estilos de controles e telas;
* Duplicação de Relatórios Telerik.
* Adicionada propriedade Columns para container LayoutCol que indica um breakpoint comum para todos os breakpoints
* Adicionada nova versão de Bootstrap.js. Popper.js e modificada a ordem de importação.
* Adicionada cópia de Breakpoints
* Adicionada propriedade SidebarAutoOpen no grupo PageLayout para definição do comportamento da Sidebar ao carregar a página.
* Adicionadas propriedades ControlPadding, TextMargin e IconMargin para controles do tipo Button.
* Acrescentada propriedade IconTextSpace para definição de espaçamento em ícones.
* Adicionada propriedade FlexDirection em containers LayoutCol.
* Adicionados os módulos de Header e Footer para definição de PageLayout em complemento ao módulo Sidebar.
* Adicionada propriedade Width \(All\) para definição de largura fixa para Sidebar.
* Adicionada propriedade Height \(All\) para definição de altura fixa para Header e Footer.

E ainda uma reestilizada no designer do Gvinci, deixando-o ainda mais bonito e amigável!😎 

Se você tem algum feedback, não deixe de compartilhar conosco em suporte@gvinci.com.br

## 2021.1.147 - 01/05/2021

### Correções

* Corrigido o problema que ocorria em projetos sem datapage. Ocorria erro de uma função faltando.

## 2021.1.146 - 23/02/2021

### Melhorias

* Melhorado código para não gerar opacidade quando a definição for 1 por ser desnecessária. Agora, a geração de opacidade quando definida como 1, não mais será gerado o código, visto que se torna desnecessário o uso de tal código em CSS.
* Melhorado a geração de definições css do grid que deixava o grid com colunas menores em sua altura. O código gerado para o grid foi melhorado nos css, pois alguns código deixava as colunas do grid menores em sua altura. Desta forma, agora o grid irá respeitar a altura definida no skin.
* Melhorado a exibição de filtro no grid quando desabilitado o botão. Os campos dos filtros acima da coluna, não estavam sendo apresentados no mesmo tamanho que os campos quando o botão estivesse desabilitado. Agora, a visualização ficou muito melhor.

## 2021.1.145 - 22/02/2021

### Novidade

* Adicionado opção para criação de ambientes de desenvolvimento \(conexões\)
* Novidade: Adicionado novas propriedades para o Grid, entre elas:
  * Exportar registro do grid para arquivos do Word\(Docx\)
  * Exportar registro do grid para arquivos para Excel \(XLSX\)
  * Adicionado propriedade ShowRefreshButton para o Grid
  * Adicionado propriedade Caption para o Grid
  * Adicionado propriedade para melhoria nos filtros do grid
  * Adicionado propriedade EnableRowHoverStyle no Grid
  * Adicionado evento RowClick no grid
  * Adicionado propriedade ValorInicial para colunas do Grid
  * Adicionado recurso para mostrar ou ocultar colunas do grid pelo usuário final da aplicação.
  * Adicionado às colunas do grid a propriedade: EmptyDataText
  * Adicionado às colunas do grid a propriedade: FooterText
  * Adicionado ao grid a propriedade: HeaderTooltip
  * Adicionado ao grid a propriedade: InsertVisiblityMode
  * Adicionado ao grid a propriedade: ShowSortIcon
  * Adicionado ao grid a propriedade: InsertItemDisplay
  * Adicionado ao grid a propriedade: ShowFooter
  * Adicionado ao grid a propriedade: EnableHeaderContextmenu
* Atualizado o componente Telerik Reporting para versão 2021.1
* Atualizado todos os componentes AJAX Telerik WebForms

### Melhorias

* Modo de abertura das propriedades, conforme ultima forma exibida.



## ?

* 
