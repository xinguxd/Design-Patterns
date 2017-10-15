  Loja Xingu


O Projeto desenvolvido foi um sistema de moedas , onde é possível comprar xingu moedas que a partir da aquisição podem ser gasta em diversas lojas do brasil. Para realizar a compra e necessário informar o nome, a quantidade moedas e o numero do cartão, após as informações básicas e necessário escolher a forma de pagamento onde temos Débito em conta e Cartão de Credito , caso débito em conta seja selecionada deve se informar o nome do Banco e em seguida a Agência, se o método de pagamento selecionado foi cartão de crédito tem que  informar a data de validade do cartão e o código CSV.
Observação : O Projeto ja está com as informações pré cadastradas para os dois métodos de pagamento.
Ao realizar a comprar e ser aprovada e entregue os pontos para o usuário, nota se que não e possível o sistema entregar os pontos duas vezes. Para realizar outra comprar é desejável que o comprador cancele ou finalize a primeira comprar para então abrir uma nova compra(instância).

Design Patterns Usados : Template,Stategy,Observe,Proxy e Singleton.

O Pattern Template ele garante a ordem de execução onde é necessário primeiro informar o nome , a quantidade de pontos o numero do cartão e a forma de pagamento . 

O Pattern Stategy foi usado mudar em tempo de execução a forma de pagamento que o usuário deseja sendo  possível mudar o método de pagamento de Debito Para Credito ou Vice Versa.

O Pattern Observe notifica o usuário que a compra foi aprovada.

O Pattern Proxy garante que ao entregar os pontos o sistema não entregue novamente pro usuário

O Pattern Singleton obriga que apenas uma instância de comprar seja abertam, ou seja o usuario deveria finalizar ou cancelar a comprar para então abrir outra compra. 
