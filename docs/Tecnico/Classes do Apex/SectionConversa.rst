#################
SectionConversa
#################

Essa classe contém as variáveis **listMensagemWa**, **isFirstSectionDate** e **sectionDate** e os metodos **SectionConversa** e **ddMensagemWa**.

Assinatura

public SectionConversa()

**Especificacoes**

@AuraEnabled
listMensagemWa

Cria a variável pública do tipo lista de MensagemWhatsapp__c.

Assinatura

public List<MensagemWhatsapp__c> listMensagemWa;

@AuraEnabled
isFirstSectionDate

Cria a variável pública do tipo Booelan.

Assinatura

public Boolean isFirstSectionDate;

@AuraEnabled
sectionDate

Cria a variável pública do tipo Date.

Assinatura

public Date sectionDate;

SectionConversa()

Cria uma lista de MensagemWhatsapp__c, vazia e a atribui na variável local listMensagemWa.

Assinatura

public SectionConversa()

Valor retornado

Sem retorno.

addMensagemWa(pMensagemWa)

Adiciona a mensagem enviada pelo parâmetro pMensagemWa a variável local listMensagemWa.

Assinatura

public void addMensagemWa(MensagemWhatsapp__c pMensagemWa)

Valor retornado

Sem retorno.
