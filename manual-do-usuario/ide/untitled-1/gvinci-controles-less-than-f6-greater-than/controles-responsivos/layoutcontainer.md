# LayoutContainer

![](../../../../../.gitbook/assets/image%20%2893%29.png)

O LayoutContainer é um container de uso geral responsivo organizado no padrão Grid, de modo que linhas e colunas possam ser adicionadas e suas larguras definidas para cada breakpoint.

Dentro de um LayoutContainer adicionamos contoles responsivos do tipo LayoutRow que representam a linha de uma grade e dentro dos controles LayoutRow adicionamos os controles do tipo LayoutCol, que representam as colunas de uma grade.

No [Bootstrap](https://getbootstrap.com/), cada breakpoint \(ponto de quebra\) foi definido para acomodar confortavelmente containers cujas larguras são múltiplas de 12. Os subconjuntos de tamanhos são representação de dispositivos de tamanhos comuns e ViewPorts. Esses intervalos de tamanhos visam fornecer uma base sólida e consistente para construção de layouts para quase todos os dispositivos.

| Ponto de quebra | Class infix | Dimensões |
| :--- | :--- | :--- |
| X-Small | _None_ | &lt;576px |
| Small | `sm` | &lt;768px |
| Medium | `md` | &lt;992px |
| Large | `lg` | &lt;1200px |
| Extra large | `xl` | &lt;1400px |

No Gvinci, os pontos de quebra são exibidos na parte superior da janela de design para os módulos definidos com LayoutResponsivo.

![](../../../../../.gitbook/assets/image%20%28101%29.png)

Assim, terá a possibilidade de definir a largura das colunas \(LayoutCol\) de modo a se adequar ao tamanho de dispositivo selecionado em cada breakpoint.

Veja também: Propriedades Controle LayoutContainer.

