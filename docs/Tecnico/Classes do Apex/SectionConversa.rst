#################
SectionConversa
#################

Essa classe cont�m as v�riaveis listMensagemWa, isFirstSectionDate e sectionDate e os m�todos SectionConversa e addMensagemWa.

Assinatura

public SectionConversa()

Explecifica��es

@AuraEnabled
listMensagemWa

Cria a vari�vel p�blica do tipo lista de MensagemWhatsapp__c.

Assinatura

public List<MensagemWhatsapp__c> listMensagemWa;

@AuraEnabled
isFirstSectionDate

Cria a vari�vel p�blica do tipo Booelan.

Assinatura

public Boolean isFirstSectionDate;

@AuraEnabled
sectionDate

Cria a vari�vel p�blica do tipo Date.

Assinatura

public Date sectionDate;

SectionConversa()

Cria uma lista de MensagemWhatsapp__c, vazia e � atribui na vari�vel local listMensagemWa.

Assinatura

public SectionConversa()

Valor retornado

Sem retorno.

addMensagemWa(pMensagemWa)

Adiciona a mensagem enviada pelo par�metro pMensagemWa � vari�vel local listMensagemWa.

Assinatura

public void addMensagemWa(MensagemWhatsapp__c pMensagemWa)

Valor retornado

Sem retorno.
