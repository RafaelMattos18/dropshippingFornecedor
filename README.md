# Dropshipping

---

Dropshipping é uma técnica de gestão da cadeia logística na qual a CONNECTPARTS não mantém os produtos em estoque, apresentando os produtos a seus clientes através da loja virtual, Marketplace e Mercado Livre.

Assim que o pedido do cliente for aprovado o pagamento (entre status pronto para manuseio e preparando entrega -verificar imagem abaixo), a ConnectParts informa a venda ao fornecedor. Dessa maneira o fornecedor emite uma nota fiscal de venda do produto pra ConnectParts que dará entrada na Nota Fiscal e fará o faturamento e então o fornecedor realizará o processo de embalagem e envio diretamente ao cliente.

A mercadoria só será enviada ao cliente via transportadora após a ConnectParts enviar a nota fiscal de faturamento desse para-choque para o fornecedor e o mesmo emitir a nota fiscal de Remessa para acompanhar a mercadoria até o cliente.

## Fluxo Básico

![](http://developers.connectparts.com.br/imagens/FluxoBasicoDropShipping.png)


No momento em que o pedido de compra é inserido no ERP da ConnectParts será disparada uma ordem de compra para o fornecedor e no mesmo momento é enviado o pedido do cliente. Após finalização das etapas acima, o fornecedor emite uma NF de venda do produto pra ConnectParts, que dará entrada na Nota Fiscal e fará o faturamento enviando a nota fiscal para o fornecedor que realizará o processo de embalagem, emissão de etiqueta e nota fiscal de venda da Connect e envio diretamente ao cliente.

A mercadoria só será enviada ao cliente via transportadora/correios após a ConnectParts enviar a NF de faturamento desse produto para o fornecedor e o mesmo emitir a NF de remessa / de NF de faturamento e etiqueta para acompanhar a mercadoria até o cliente.

Quando um pedido dropshipping for faturado pela Connect, ele não será despachado pela Connect, dessa forma assim que ele for faturado, a Logística da Connect altera o status no ERP para despachado, lembrando que o pedido será despachado até 24 horas conforme informamos no e-mail para o cliente. 