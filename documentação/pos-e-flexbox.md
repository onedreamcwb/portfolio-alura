#  Seletor de Classe
*  permite ao CSS selecionar e acessar elementos específicos através dos seletores de classe, "." https://developer.mozilla.org/pt-BR/docs/Web/HTML/Global_attributes/class

## Nomes de classes no CSS

* Quer entender as boas práticas para dar um nome nas classes do CSS?
https://www.alura.com.br/artigos/nomes-de-classes-no-css

## No centro do SMACSS está a categorização. 
Ao categorizar as regras CSS, começamos a ver padrões e podemos definir melhores práticas em torno de cada um desses padrões.

Existem cinco tipos de categorias:

* Base
* Disposição
* Módulo
* Estado
* Tema

## Regras básicas

são os padrões. Eles são quase exclusivamente seletores de elemento único, mas podem incluir seletores de atributo, seletores de pseudoclasse, seletores filhos ou seletores irmãos. Essencialmente, um estilo base diz que onde quer que este elemento esteja na página, ele deve se parecer com isto .


html
```
html, body, form { margin: 0; padding: 0; }
input[type=text] { border: 1px solid #999; }
a { color: #039; }
a:hover { color: #03C; }
```
# Seletores

## Por Tag
nome-da-tag Exemplo: `input` corresponderá a qualquer elemento `<input>`. 

## Por Classe
Este seletor básico escolhe elementos baseados no valor de seu atributo `class`. Sintaxe: `.nome-da-classe` 
Exemplo: 
* .index 

irá corresponder a qualquer elemento que tenha o índice de classe (provavelmente definido por um atributo class="index", ou similar).

## Seletor por ID
Este seletor básico escolhe nós baseados no valor do atributo id. Deve existir apenas um elemento com o mesmo ID no mesmo documento. Sintaxe: #nome-do-id Exemplo: #toc irá corresponder ao elemento que possuir o id=toc (definido por um atributo id="toc", ou similar).

Saiba mais : https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Selectors


## As regras de layout

* dividem a página em seções. Os layouts mantêm um ou mais módulos juntos.

## Os módulos

* São as partes reutilizáveis ​​e modulares do nosso design. Eles são as chamadas, as seções da barra lateral, as listas de produtos e assim por diante.

## Regras de estado
* são maneiras de descrever como nossos módulos ou layouts ficarão quando estiverem em um determinado estado. Está oculto ou expandido? É ativo ou inativo? Eles descrevem a aparência de um módulo ou layout em telas menores ou maiores. Eles também descrevem como um módulo pode parecer em diferentes visualizações, como a página inicial ou a página interna.

## Temas
*  são semelhantes às regras de estado, pois descrevem a aparência dos módulos ou layouts. A maioria dos sites não requer uma camada de temas, mas é bom estar ciente disso.



# Height e box-sizing

Box-Sizing
https://www.w3schools.com/css/css3_box-sizing.asp

# O que é Viewport

* Em computação gráfica, a viewport é a porção de área visível de um plano e é utilizada como unidade de medida no CSS para criar páginas Web 100% responsivas.

Site pra se aprofundar: https://www.alura.com.br/artigos/guia-de-unidades-no-css

# FlexBox

Referencias :

 https://cursos.alura.com.br/search?query=flexbox

CSS flexbox designs responsivos:
 https://cursos.alura.com.br/course/css-flexbox-layouts-responsivos

Complete Guide:
 
https://css-tricks.com/snippets/css/a-guide-to-flexbox/

