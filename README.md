# aulas-front-end

 atividades de estudo HTML e CSS

## html

- estruturas
- semântica
- Padrões

## CSS

Linguagem de estilização que "casa" com elementos do html.

em geral css serve para:

1. estilos (cor, sombra, borda, etc...)
2. alinhamento e espaçamentos
3. design responsivo
4. animações e efeitos especiais


### Formas de implementação

#### inline (não recomendado)

o CSS é aplicado diretamente em cada tag HTML.

#### interna/onpage (quebra o galho)

o CSS é criado usando regras (com seletores, propriedades, valores) dentro da própria página que queremos formatar.

as regras vão valer para todos os elementos/tags desta página.

#### como fazer uma regra CSS?

seletor {propriedade: valor; }

seletor {propriedade0: valor;
propriedade1: valor;
propriedade2: valor;

}

#### externa (mais usado!)

é criado um arquivo de extensão CSS dedicado as regras de formatação. Este aquivo é então "conectado" às páginas HTML.

---
### Tipos de seletor
-tag: (seletor mais abrangente/generalista casa com elementos de html por tag especifica)

-descendente: (seletor mais especifico, casa com elementos que sao filhos/descendentes de outro elemento. usa-se espaço para separar o filho/pai)

-agrupado: (grupo de seletores que compartilham uma mesma formatação, usa-se virgula para separar os seletores.)

-pseudo-classe: (classes pré prontas da linguagem que podem ser aplicadas em diversas situações. exemplos: passar mouse, reconhecer foco, selecionar determinados elementos etc. Todos pseudo-classes começam com dois-pontos ":" .)

-classe: (Seletor versatil que permite a aplicação de estilos me diversos elementos, possibilita tambem a combinação de diferentes classes. no CSS usa-se .nome-da-classe para cliar a classe, e no html usa-se o atributo class="nome-da-classe" para aplicar a classe.)

-identificado: (Seletor bastante restrito so pode ser usado um elemento por pagina permitindo criar uma estilização altamente especifica, no CSS usa-se #nome-do-id para criar, e no html usa-se o atributo id="nome-do-id" para aplicar.)


## JS
