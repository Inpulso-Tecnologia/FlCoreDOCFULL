#################
Desinstalação de Pacote
#################

É possível desinstalar o Falae da sua organização, mas para isso é necessário a desinstalação manual de algumas dependências do pacote. Começaremos com a desativação dos Process Builders. Para encontrá-los basta ir em Configuração e procurar por "Process Builder" na barra de pesquisa:
 
.. figure:: img/Desinstalar4.png
    :width: 200px
    :alt: Solidity logo
    :align: center
    
    Process Builder

Após encontrá-los, basta clicar na seta para expandir as opções e selecionar "Desativar". Para que a desinstalação tenha sucesso é necessário que todos os Process Builders sejam desativdos.

.. figure:: img/Desinstalar5.png
    :width: 950px
    :alt: Solidity logo
    :align: center
    
    Desativação do Process Builder
    
Será necessário também remover o metadado Parâmetro Global. O Parâmetro Global pode ser encontrado pesquisando por "Metadado" na barra de pesquisa na Configuração

.. figure:: img/Desinstalar6.png
    :width: 250px
    :alt: Solidity logo
    :align: center
    
    Metadados "Gerenciar Registros" ao lado do Parâmetro Global. 
    
Nos metadados, deve ser selecionado o botão "Gerenciar Registros" que se encontra ao lado do metadado Parâmetro Global     
    
.. figure:: img/Desinstalar7.png
    :width: 350px
    :alt: Solidity logo
    :align: center
    
    Gerenciar Registros do Parâmetro Global
    
Ao selecionar a opção, dois registros serão mostrados em tela, ambos precisam ser excluídos para que a desinstalação seja possível

.. figure:: img/Desinstalar8.png
    :width: 700px
    :alt: Solidity logo
    :align: center
    
    Instancias do servidor Mob e Web

Após a realização da exclusão do Parâmetro Global, será necessária a exclusão dos dados do Site Remoto

.. figure:: img/Desinstalar9.png
    :width: 250px
    :alt: Solidity logo
    :align: center
    
    Site Remoto
        
No site remoto deve-se excluir ambos os registros, WhatsappMob e WhatsappWeb.

.. figure:: img/Desinstalar10.png
    :width: 700px
    :alt: Solidity logo
    :align: center
    
    Exclusão do Site Remoto
 
Estes são os padrões, entretanto pode-se encontrar algumas outras dependencias do pacote caso o mesmo já tenha sido customizado, como por exemplo um campo do Falae sendo utilizado em um Layout padrão

.. figure:: img/Desinstalar11.png
    :width: 700px
    :alt: Solidity logo
    :align: center
    
    Campo do Falae no Objeto Caso
    
Os campos são facilmente removidos arrastando-os de volta para a barra superior    
  
.. figure:: img/Desinstalar12.png
    :width: 480px
    :alt: Solidity logo
    :align: center
    
    Remoção do campo
 
Pode também haver Layouts implantados e estes também precisam ser removidos, para removê-los é necessário acessar o Objeto através do Gerenciador de Objetos e ir na aba de Layout 
 
.. figure:: img/Desinstalar13.png
    :width: 700px
    :alt: Solidity logo
    :align: center
    
    Layouts Customizados nos Objetos
 
Depois da remoção das dependências a desinstalação pode ser realizada através dos Pacotes Instalados e para acessá-lo basta entrar em Configuração e procurar por "Pacotes Instalados"

.. figure:: img/Desinstalar1.png
    :width: 250px
    :alt: Solidity logo
    :align: center
    
    Pacotes Instalados

Nos Pacotes Instalados é possível visualizar todos os pacotes instalados em sua organização, além de poder desinstalá-los. Para a desinstalação é necessário selecionar a ação "Desinstalar"

.. figure:: img/Desinstalar2.png
    :width: 700px
    :alt: Solidity logo
    :align: center
    
    Desinstalação
    
No final da página será necessário marcar a opção confirmando que deseja desinstalar permanentemente os componentes e clickar no botão "Desinstalar"

.. figure:: img/Desinstalar3.png
    :width: 700px
    :alt: Solidity logo
    :align: center
    
    Confirmação da Desinstalação
    
Ao confirmar, a desinstalação do Falae será iniciada.
