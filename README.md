# Aula 01 - Introdu��o ao Javaserver Faces

## M�dulo Avan�ado Curso: T�cnico IMD  


* Conhecer qual � a estrutura de uma aplica��o b�sica com JSF.

* Criando uma Aplica��o B�sica Web


O JavaServer Faces (JSF) � um framework MVC para desenvolvimento de aplica��es web utilizando Java no lado servidor. Ele � composto por:

* Uma biblioteca para representa��o dos componentes HTML nas p�ginas web;
* Conversores de dados;
* Validadores e tratadores de erros.

Todos esses itens que comp�em o JSF s�o importantes para a cria��o de aplica��es web. Com isso, utilizando esses itens poderemos criar p�ginas web colocando componentes nas mesmas para que possamos manipul�-los, lig�-los a m�todos de classes Java que realizar�o determinados processamentos no lado servidor.


Uma aplica��o web desenvolvida com JSF � similar a qualquer outra aplica��o web desenvolvida com outro framework para Java. Dessa forma, ao analisarmos uma aplica��o JSF t�pica encontraremos as seguintes partes:

*Um conjunto de p�ginas XHTML denominadas facelets, representando a view do MVC. Cada p�gina XHTML possui uma �rvore de componentes JSF;
*Um conjunto de classes Java denominadas managed beans, que representam o controller do MVC;
*Um conjunto de classes de dom�nio referentes ao neg�cio da aplica��o, representando o model do MVC;
*O descritor de implanta��o web (arquivo web.xml).


Poderemos, tamb�m, encontrar um ou mais arquivos de configura��o da aplica��o JSF denominados faces-config.xml. Esses arquivos, que a partir da vers�o do JSF 2.0 se tornaram opcionais, definem principalmente as regras de navega��o da aplica��o. A Figura 1 apresenta como ocorre a resposta a uma requisi��o vinda de um navegador em uma aplica��o JSF.


A principal caracter�stica do JSF � que o mesmo possibilita a separa��o clara entre o comportamento e a apresenta��o nas aplica��es web. Essa separa��o permite que o desenvolvimento e a manuten��o da aplica��o web sejam realizados de maneira mais f�cil, o que corresponde a menos retrabalho.

## Ciclo de Vida

Agora que voc� j� conhece o que � o JSF, vamos conhecer e entender o ciclo de vida de uma requisi��o para uma aplica��o desenvolvida com esse framework e como sua resposta � gerada. O ciclo de vida do JSF, apresentado na Figura 2, � composto pelas seguintes fases:


 **1**. restaurar a visualiza��o;
 **2**. aplicar valores da requisi��o;
 **3**. processar as valida��es;
 **4**.atualizar os valores no modelo;
 **5**. invocar a aplica��o;
 **6**. renderizar a resposta.
