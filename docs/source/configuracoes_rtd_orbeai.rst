Título
======

Para criar um título do tópico, basta escrecer o nome do título/tópico e vários sinais de iguais debaixo dele até o final do nomedotítulo.


Primeiro tópico
---------------

Para criar um tópico na página (que já é referenciado no menu da barra lateral), basta escrever o nome do tópico e debaixo dele um monte de traços até o final do nome do tópico.
Obs: no teclado Apple, estes traços são a tecla (sem apertar SHIFT) do lado direito do ZERO e antes do sinal de igual.

Como fazer subtópicos? Acho que é ==== para tópico e ------- para subtópico.

.. topic:: Título do tópico

   Este é o texto que vai no tópico.
   
Sidebar
-------

.. sidebar:: Sidebar Title
   :subtitle: Optional Subtitle

   This is a sidebar.  It is for text outside the flow of the main
   text.

   .. rubric:: This is a rubric inside a sidebar

   Sidebars often appears beside the main text with a border and
   background color.


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

Este é o link "Python_"

.. _Python: http://www.python.org/

Figuras
-------


Campos de atenção
-----------------

.. Attention:: Directives at large.

.. Caution:: Don't take any wooden nickels.

.. DANGER:: Mad scientist at work!

.. Error:: Does not compute.

.. Hint:: It's bigger than a bread box.

.. Important::
   - Wash behind your ears.
   - Clean up your room.

     - Including the closet.
     - The bathroom too.

       - Take the trash out of the bathroom.
       - Clean the sink.
   - Call your mother.
   - Back up your data.

.. Note:: This is a note.
   Equations within a note:
   :math:`G_{\mu\nu} = 8 \pi G (T_{\mu\nu}  + \rho_\Lambda g_{\mu\nu})`.

.. Tip:: 15% if the service is good.

    +---------+
    | Example |
    +=========+
    | Thing1  |
    +---------+
    | Thing2  |
    +---------+
    | Thing3  |
    +---------+

.. WARNING:: Strong prose may provoke extreme mental exertion.
   Reader discretion is strongly advised.

.. admonition:: And, by the way...

   You can make up your own admonition too.
   



