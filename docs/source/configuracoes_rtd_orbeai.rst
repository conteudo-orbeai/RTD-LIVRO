Título
======

Para criar um título do tópico, basta escrecer o nome do título/tópico e vários sinais de iguais debaixo dele até o final do nomedotítulo.


Primeiro tópico
---------------

Para criar um tópico na página (que já é referenciado no menu da barra lateral), basta escrever o nome do tópico e debaixo dele um monte de traços até o final do nome do tópico.
Obs: no teclado Apple, estes traços são a tecla (sem apertar SHIFT) do lado direito do ZERO e antes do sinal de igual.


Inserir código Python
----------------------

Para inserir código como se fosse o terminal, basta usar o code-block desta forma:

.. code-block:: console

  $ pip install streamlit
  
Para inserir código Python com número das linhas e destaque de algumaslinhas, basta usar o code-block desta forma:

.. code-block:: python
  :linenos:
  :emphasize-lines: 3,5
  
  def some_function( ):
    i = False
    print('Esta é uma linha destacada')
    print('Esta não é uma linha destacada')
    print('já esta linha é destacada')
    
Fazer um glossário
------------------

Para fazer um glossário, basta usar o termo .. glossary:: desta forma:

.. glossary::

  Documentação
    Provê para os usuários, todos os comantos que precisa.
    
  Leitura
    A leitura deve ser rápida e clara.
    
Hiperlinks
----------

Para criar hiperlinks que levem para outro site, usamos esta sintaxe (onde ..Python: é onde usuário pode clicar para ir para o site.

..Python: https://www.python.org/

