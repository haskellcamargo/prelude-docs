.. _sintaxe_basica:

==============
Sintaxe Básica
==============

O Prelude HB/AdvPL também estende uma sintaxe específica através do pré-processador, permitindo várias formas de expressar uma mesma coisa e, ainda, mantendo compatibilidade com código legado.

------
Padrão
------

A sintaxe padrão é definida por ``@Funcao { Argumentos ... }``, onde os argumentos são separados por ``,``. Exemplos:

.. literalinclude:: demo/sintaxe.hb
   :language: xbase
   :linenos:

--------------
O operador ::=
--------------

O operador ``::=`` pode aqui ser conhecido como "aplicação de bloco". Ele serve para funções do Prelude que recebam somente 2 argumentos, sendo estes listas e blocos. São, basicamente, uma abstração:

.. literalinclude:: demo/operador.hb
   :language: xbase
   :linenos: