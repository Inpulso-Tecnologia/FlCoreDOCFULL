#################
SectionConversa
#################

Essa classe cont�m as vari�veis **listMensagemWa**, **isFirstSectionDate** e **sectionDate** e os metodos **SectionConversa** e **ddMensagemWa**.

Assinatura

public SectionConversa()

**Especificacoes**

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

Cria uma lista de MensagemWhatsapp__c, vazia e a atribui na vari�vel local listMensagemWa.

Assinatura

public SectionConversa()

Valor retornado

Sem retorno.

addMensagemWa(pMensagemWa)

Adiciona a mensagem enviada pelo par�metro pMensagemWa a vari�vel local listMensagemWa.

Assinatura

public void addMensagemWa(MensagemWhatsapp__c pMensagemWa)

Valor retornado

Sem retorno.
