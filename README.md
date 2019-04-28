# Aula 01 - Introdução ao Javaserver Faces

## Módulo Avançado Curso: Técnico IMD  


* Conhecer qual é a estrutura de uma aplicação básica com JSF.

* Criando uma Aplicação Básica Web


O JavaServer Faces (JSF) é um framework MVC para desenvolvimento de aplicações web utilizando Java no lado servidor. Ele é composto por:

* Uma biblioteca para representação dos componentes HTML nas páginas web;
* Conversores de dados;
* Validadores e tratadores de erros.

Todos esses itens que compõem o JSF são importantes para a criação de aplicações web. Com isso, utilizando esses itens poderemos criar páginas web colocando componentes nas mesmas para que possamos manipulá-los, ligá-los a métodos de classes Java que realizarão determinados processamentos no lado servidor.


Uma aplicação web desenvolvida com JSF é similar a qualquer outra aplicação web desenvolvida com outro framework para Java. Dessa forma, ao analisarmos uma aplicação JSF típica encontraremos as seguintes partes:

*Um conjunto de páginas XHTML denominadas facelets, representando a view do MVC. Cada página XHTML possui uma árvore de componentes JSF;
*Um conjunto de classes Java denominadas managed beans, que representam o controller do MVC;
*Um conjunto de classes de domínio referentes ao negócio da aplicação, representando o model do MVC;
*O descritor de implantação web (arquivo web.xml).


Poderemos, também, encontrar um ou mais arquivos de configuração da aplicação JSF denominados faces-config.xml. Esses arquivos, que a partir da versão do JSF 2.0 se tornaram opcionais, definem principalmente as regras de navegação da aplicação. A Figura 1 apresenta como ocorre a resposta a uma requisição vinda de um navegador em uma aplicação JSF.


A principal característica do JSF é que o mesmo possibilita a separação clara entre o comportamento e a apresentação nas aplicações web. Essa separação permite que o desenvolvimento e a manutenção da aplicação web sejam realizados de maneira mais fácil, o que corresponde a menos retrabalho.

## Ciclo de Vida

Agora que você já conhece o que é o JSF, vamos conhecer e entender o ciclo de vida de uma requisição para uma aplicação desenvolvida com esse framework e como sua resposta é gerada. O ciclo de vida do JSF, apresentado na Figura 2, é composto pelas seguintes fases:


 **1**. restaurar a visualização;
 **2**. aplicar valores da requisição;
 **3**. processar as validações;
 **4**.atualizar os valores no modelo;
 **5**. invocar a aplicação;
 **6**. renderizar a resposta.
