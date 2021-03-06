############################
WAInbox
############################
Atributos
------------
+------------------------+-----------------------+-------------+
|  name                  | Tipo                  | Obrigatório |
+========================+=======================+=============+
| Status                 | String[]              | false       | 
+------------------------+-----------------------+-------------+
| chatStatus             | String[]              | false       | 
+------------------------+-----------------------+-------------+
| conversas              | ConversaWhatsapp__c[] | false       | 
+------------------------+-----------------------+-------------+
| idTabConversa          | String                | false       | 
+------------------------+-----------------------+-------------+
| acoes                  | AcaoWhatsapp__mdt[]   | false       | 
+------------------------+-----------------------+-------------+
| usuario                | User                  | false       | 
+------------------------+-----------------------+-------------+
| numerosAgente          | String                | false       | 
+------------------------+-----------------------+-------------+
| sessionId              | String                | false       | 
+------------------------+-----------------------+-------------+
| dataHoraDisponibilidade| DateTime              | false       | 
+------------------------+-----------------------+-------------+
| statusDisponibilidade  | String                | false       | 
+------------------------+-----------------------+-------------+
| timerId                | String                | false       | 
+------------------------+-----------------------+-------------+
| timer                  | String                | false       | 
+------------------------+-----------------------+-------------+
| temAgente              | Boolean               | false       | 
+------------------------+-----------------------+-------------+
| countNotificacao       | Integer               | false       | 
+------------------------+-----------------------+-------------+
| labelUtilityBar        | Integer               | false       | 
+------------------------+-----------------------+-------------+
| isHighlighted          | Boolean               | false       | 
+------------------------+-----------------------+-------------+
Exemplo
---------

.. code-block:: apex

   <aura:attribute name="exemp" type="String" default = "Logout">
   <whats:WACoreActionRelacionamento
                              status = {!v.exemp}>
                              
                              
   .. code-block:: html

      <aura:component extends="whats:WAInbox" >
         <!-- Header -->
         <aura:handler name="init" value="{!this}" action="{!c.doInit}"/>
         <aura:handler name="onReceiveMessage" event="c:WAStreamEvent" action="{!c.handleReceivedMessage}" />
         <aura:handler name="onClick" event="c:WAInboxConversaEvent" action="{!c.handleClickConversa}" />

         <!-- Content -->
         <div id="contentWAInbox" class="fullscreen">
          <div class="c-container layoutAgent">
           <lightning:layout>  
            <lightning:layoutItem flexibility="auto" padding="around-small" size="9">
               <lightning:tile label="{!v.usuario.Name}" href="{!'/'+v.usuario.Id}">
                  <ul class="slds-list_horizontal slds-has-dividers_right">
                     <li class="slds-item">
                        <span class="clabel">Números: </span>&nbsp;<span data-bind="html:AgentExtension">
                     </li>
                  </ul>
               </lightning:tile>
            </lightning:layoutItem>
           </lightning:layout>
          </div>  
         </div>
                              
Function
----------
onChangeUserStatus
~~~~~~~~
 Não está em uso

doInit
~~~~~~~~
 Estabelece a conexão com o host

scriptsLoaded
~~~~~~~~
 Inicia uma série de ações do helper, como carregar o usuário, mostrar as conversas vistas

onSelectWAAction
~~~~~~~~
 executa o método doExecuteAction

onSelectConversa
~~~~~~~~
 Retorna mensagens conversa e organiza-as

handleReceivedMessage
~~~~~~~~
 Recebe um JSON com as mensagens enviadas para a conversa

handleClickConversa
~~~~~~~~
 Atribui valores a variável listConversa e aciona outras functions "loadActions" e "setSeenSelectedConversa"
