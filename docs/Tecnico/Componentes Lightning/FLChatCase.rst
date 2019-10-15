#################
FLChatCase
#################

Funcionalidade
~~~~~~~~~~

O componente FLChatCase serve para mostrar a conversa relacionada ao caso enviado por parâmetro.


Atributos:
~~~~~~~~~~~~

+------------------------+-----------------------+
|  name                  | Tipo                  |
+========================+=======================+
| height                 | Integer               |
+------------------------+-----------------------+
| caso                   | Case                  |
+------------------------+-----------------------+


Exemplo
~~~~~~~~~~

.. code-block:: html

  <aura:attribute name="casoParam" type="Case" />
  
  <flcore:FLChatCase height="800" caso="casoParam" />
