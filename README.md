# **IFSP LIFE** - *Sistema Intranet Farmácia*
<h2>
 <img src = "https://raw.githubusercontent.com/rahulbanerjee26/githubProfileReadmeGenerator/main/gifs/code.gif" width = 32px height=32px> 
 Linguagens e Ferramentas Utilizadas no Projeto: 
 <img src = "https://raw.githubusercontent.com/rahulbanerjee26/githubProfileReadmeGenerator/main/gifs/code.gif" width = 32px height=32px> </h2>
<a href= https://github.com/?tab=repositories&q=&type=&language=java&sort= > <img width ='32px' height='32px' src ='https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/java.svg'> </a>
<a href= https://github.com/?tab=repositories&q=&type=&language=java&sort= > <img width ='32px' height='32px' src ='https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/java.svg'> </a>
<a href= https://github.com/?tab=repositories&q=&type=&language=java&sort= > <img width ='32px' height='32px' src ='https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/java.svg'> </a>
<a href= https://github.com/?tab=repositories&q=&type=&language=java&sort= > <img width ='32px' height='32px' src ='https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/java.svg'> </a>

# CAPÍTULO 1 - INTRODUÇÃO AO SISTEMA E ESCOPO
**Descrição do Sistema:**<br>
O sistema IFSP-LIFE será implementado em uma farmácia com o objetivo 
principal de automatizar e otimizar o processo de venda de produtos, além de garantir 
uma gestão eficaz do estoque, convênios e fornecedores, promovendo maior 
eficiência e segurança nas operações diárias. Durante o atendimento ao cliente, este 
seleciona os produtos disponíveis na farmácia, e o funcionário, utilizando o sistema, 
localiza os valores previamente cadastrados. Quando a venda é finalizada, o sistema 
calcula automaticamente o valor total, e o funcionário solicita ao cliente a forma de 
pagamento. Se o pagamento for realizado via cartão, o valor é registrado no sistema. 
Caso seja em dinheiro, o sistema calcula o troco que deverá ser devolvido ao cliente.<p>

O IFSP-LIFE também permitirá a gestão do estoque, controlando a validade dos 
produtos, emitindo alertas de vencimento e notificando sobre a necessidade de 
reposição. Essa funcionalidade inclui a possibilidade de reordenar itens 
automaticamente quando os níveis de estoque atingirem um ponto crítico, 
assegurando que a farmácia esteja sempre bem abastecida. O sistema ainda contará 
com recursos para gerenciar convênios e fornecedores, onde o Administrador poderá 
cadastrar e atualizar informações, como dados de contato e condições de pagamento.     
O sistema permitirá a aplicação de descontos especiais para convênios específicos, 
incentivando a fidelização de clientes conveniados.<p>

Além disso, o sistema gerará relatórios gerenciais, permitindo ao Administrador 
analisar o desempenho da farmácia em aspectos como vendas, movimentação de 
estoque, convênios e fornecedores. Com essas informações em mãos, o 
administrador terá uma base sólida para tomar decisões estratégicas e implementar 
melhorias que possam otimizar o desempenho da farmácia e garantir a satisfação dos 
clientes.<p>

Por fim, o sistema tem dois níveis de acesso, o Administrador e o Funcionário. 
O nível de acesso Funcionário tem permissão para atender aos clientes e realizar 
pedidos no estabelecimento, enquanto o nível de acesso Administrador proporcionará 
controle total do sistema, incluindo a manutenção de dados, gestão de convênios, 
fornecedores e estoque, bem como a compra de novos itens. Em resumo, o IFSP
LIFE é um software completo que visa melhorar a eficiência e a gestão nas redes 
farmacêuticas.

# Capítulo 3 - Definição de Funções
Este capítulo descreve as funções que serão implementadas no sistema, cada uma delas desempenhando um papel essencial nas operações da farmácia.


### Requisitos Fundamentais
- **Func. Fundamental 1.0 - Efetuar Compra:** Registra novos pedidos de compra aos fornecedores e atualiza o estoque.<p>
- **Func. Fundamental 1.1 - Efetuar Pagamento Compra:** Realiza o pagamento e registro das parcelas.<p>
- **Func. Fundamental 1.2 - Efetuar Venda:** Permite que os funcionários realizem vendas a venda de produtos e atualiza o estoque.<p>
- **Func. Fundamental 1.3 - Abrir Caixa:** Abre o caixa para o início das operações diárias, registrando o valor inicial.<p>
- **Func. Fundamental 1.4 - Fechar Caixa:** Encerra o expediente, finalizando as operações diárias e atualizando o saldo do caixa.<p>
- **Func. Fundamental 1.5 - Efetuar Sangria:** Permite a retirada de valores do caixa, registrando a sangria para controle financeiro.<p>
- **Func. Fundamental 1.6 - Efetuar Suplementação:** Permite adicionar valores ao caixa, registrando a suplementação para controle financeiro.<p>

### Requisitos Básicos

- **Func. Básica 1.0 - Manter Produtos:** Gerencia o cadastro de produtos.
- **Func. Básica 1.1 - Manter Fornecedores:** Gerencia informações sobre fornecedores.
- **Func. Básica 1.2 - Manter Funcionários:** Gerencia o cadastro de funcionários.
- **Func. Básica 1.3 - Manter Convênios:** Gerencia convênios e parcerias.

### Requisitos de Saída

- **Func. Saída 1.0 - Gerar Relatório dos Produtos:** Gera relatórios sobre o estoque de produtos.
- **Func. Saída 1.1 - Gerar Relatório de Vendas:** Produz relatórios de vendas realizadas.
- **Func. Saída 1.2 - Gerar Relatório de Compras:** Gera relatórios sobre compras efetuadas.

### Regras de Negócio
- **Regra de Negócio 1.0 -  Aplicar Desconto para Produtos Próximos ao Vencimento: Aplica descontos a produtos que estão próximos do vencimento.** 
- **Regra de Negócio 1.1 -  Gerenciar Promoções Temporárias: Permite a criação e gerenciamento de promoções temporárias**
- **Regra de Negócio 1.2 -  Notificação de Reposição Antecipada: Emite notificações quando os níveis de produtos estiverem baixos,**
- **Regra de Negócio 1.3 -  Alerta de Vencimento: Emite alertas sobre produtos com data de vencimento próxima,**

# Capítulo 4 - Requisitos Específicos

### Diagrama de Caso de Uso
![Diagrama de Caso de Uso](link-para-imagem-do-diagrama)
<hr>

## Especificação Textual dos Casos de Uso

- **Caso: Efetuar Venda**  
  Especificação: [Link para especificação](link-para-especificacao-venda.txt)
  
- **Caso: Abrir Caixa**  
  Especificação: [Link para especificação](link-para-especificacao-abertura-caixa.txt)

- **Caso: Fechar Caixa**  
  Especificação: [Link para especificação](link-para-especificacao-fechamento-caixa.txt)

- **Caso: Efetuar Sangria**  
  Especificação: [Link para especificação](link-para-especificacao-sangria.txt)

- **Caso: Efetuar Suplementação**  
  Especificação: [Link para especificação](link-para-especificacao-suplementacao.txt)

- **Caso: Efetuar Compra**  
  Especificação: [Link para especificação](link-para-especificacao-compra.txt)

- **Caso: Manter Fornecedor (CRUD)**  
  Especificação: [Link para especificação](link-para-especificacao-compra.txt)


## Diagrama de Atividade
![Diagrama de Atividade](link-para-imagem-do-diagrama-de-atividade)

<hr>

- **Atividade: Processo de Compra**  
  Link para imagem: [link-para-imagem-do-processo-de-compra](link-para-imagem-do-processo-de-compra.png)