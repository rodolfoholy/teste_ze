# QA Challenge

## Identify critical flows

**Signup**
Por ser a porta de entrada de novos usuário, o aplicativo não pode deixar de ter o crescimento de sua massa de clientes diariamente. Vejo ele como o fluxo mais crítico justamente pela busca de crescimento dessa massa, e também que o usuário não consegue finalizar um pedido sem realizar o cadastro primeiro. 

**Login**: 
Esse é o segundo mais importante, pois possibilita que o usuário consiga logar na plataforma, acessar o cardápio de bebidas e finalize a compra. Segundo testado na automação mobile, não é possível realizar o pedido sem que o usuário esteja logado.

**Pagamento on-line** 
Por se tratar de conter dados de segurança dos usuários, esse fluxo deve ser muito bem verificado para não comprometer as informações de cartões de nossos usuários. Ele não estava na lista de fluxos críticos pois, ao testar o pedido no aplicativo, a opção não tinha aparecido para mim, apenas hoje testando novamente foi possível ser feito o pagamento on-line, então não são todos os parceiros que possuem essa opção como descrito no FAQ.
Ressalto, porém sem o cardápio de bebidas o cliente não consegue selecionar o produto. Pensei na questão da busca por endereço, mas o cliente consegue inserir o endereço manualmente (como demonstrado na automação), e sem esse processo o cliente também não chega na finalização do pedido e nem na sacola. O fato de não ver produtos disponíveis pode causar desconforto ao cliente. 
