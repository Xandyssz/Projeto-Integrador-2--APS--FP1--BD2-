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
![Diagrama de Caso de Uso](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20Caso%20de%20Uso%20-%20ok/DCU-Principal.png)

<hr>

## Especificação Textual dos Casos de Uso

- **Caso: Abrir Caixa**  
  Especificação: [Abrir Caixa](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Abrir%20Caixa%20-%20ok/Especifica%C3%A7%C3%A3o%20Textual%20%5BAbrir%20Caixa%5D.txt)

- **Caso: Efetuar Compra**  
  Especificação: [Efetuar Compra](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Efetuar%20Compra%20-%20ok/Especifica%C3%A7%C3%A3o%20Textual%20%5BEfetuar%20Compra%5D.txt)

- **Caso: Efetuar Venda**  
  Especificação: [Efetuar Venda](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Efetuar%20Venda%20-%20ok/Especifica%C3%A7%C3%A3o%20Textual%20%5BEfetuar%20Venda%5D.txt)

- **Caso: Fechar Caixa**  
  Especificação: [Fechar Caixa](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Fechar%20Caixa%20-%20ok/Especifica%C3%A7%C3%A3o%20Textual%20%5BFechar%20Caixa%5D.txt)

- **Caso: Pagar Fornecedor**  
  Especificação: [Pagar Fornecedor](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Pagar%20Fornecedor%20-%20ok/Especifica%C3%A7%C3%A3o%20Textual%20%5BPagar%20Fornecedor%5D.txt)

- **Caso: Efetuar Sangria**  
  Especificação: [Efetuar Sangria](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Realizar%20Sangria%20Caixa%20-%20ok/Especifica%C3%A7%C3%A3o%20Textual%20%5BRealizar%20Sangria%5D.txt)

- **Caso: Efetuar Suplementação**  
  Especificação: [Efetuar Suplementação](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Realizar%20Suprimento%20Caixa%20-%20ok/Especifica%C3%A7%C3%A3o%20Textual%20%5BSuplementa%C3%A7%C3%A3o%20Caixa%5D.txt)

- **Caso: Receber Produto**  
  Especificação: [Receber Produto](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Receber%20Produtos/Especifica%C3%A7%C3%A3o%20Textual%20%5BReceber%20Produtos%5D.txt)

- **Caso: Receber Pagamento**  
  Especificação: [Receber Pagamento](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Receber%20Pagamento%20-%20ok/Especifica%C3%A7%C3%A3o%20Textual%20%5BReceber%20Pagamento%5D.txt)

- **Caso: Manter Funcionário (CRUD)**  
  Especificação: [CRUD Funcionário](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Manter%20Funcion%C3%A1rio%20-%20OKK/Especifica%C3%A7%C3%A3o%20Textual%20%5BCRUD%20Funcion%C3%A1rio%5D.txt)

### Diagramas de Atividade

- [Diagrama de Atividade - Abrir Caixa](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Abrir%20Caixa%20-%20ok/DEA-Abrir_Caixa.png)

- [Diagrama de Atividade - Efetuar Compra](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Efetuar%20Compra%20-%20ok/DEA_EfetuarCompra.png)

- [Diagrama de Atividade - Efetuar Venda](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Efetuar%20Venda%20-%20ok/DEA_EfetuarVenda.png)

- [Diagrama de Atividade - Fechar Caixa](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Fechar%20Caixa%20-%20ok/DEA-Fechar_Caixa.png)

- [Diagrama de Atividade - Pagar Fornecedor](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Pagar%20Fornecedor%20-%20ok/DEA_PagarFornecedor.png)

- [Diagrama de Atividade - Realizar Sangria](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Realizar%20Sangria%20Caixa%20-%20ok/DEA_RealizarSangriaCaixa.png)

 - [Diagrama de Atividade - Realizar Suplementação](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Realizar%20Suprimento%20Caixa%20-%20ok/DEA_RealizarSuprimentoCaixa.png)

- [Diagrama de Atividade - Receber Pagamento](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Receber%20Pagamento%20-%20ok/DEA_ReceberPagamento.png)

- [Diagrama de Atividade - Receber Produtos](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Receber%20Produtos/DEA_ReceberProdutos.png)
  
### CRUD Funcionário
- [Diagrama de Atividade - CRUD Funcionário Inserir](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Manter%20Funcion%C3%A1rio/DA-Incluir%20Funcion%C3%A1rio.png) | desenvolvimento
- [Diagrama de Atividade - CRUD Funcionário Alterar](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Manter%20Funcion%C3%A1rio%20-%20OKK/DEA_Editar%20Funcion%C3%A1rio.png)
- [Diagrama de Atividade - CRUD Funcionário Remover](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Manter%20Funcion%C3%A1rio%20-%20OKK/DEA_Excluir%20Funcion%C3%A1rio.png)
- [Diagrama de Atividade - CRUD Funcionário Consultar](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade%20-%20ok/Manter%20Funcion%C3%A1rio%20-%20OKK/DEA_Visualizar%20Funcion%C3%A1rio.png)
<hr>

# Capítulo 5 - Projeto de Software
### Arquitetura Lógica de Software
![Arqutietura Lógica de Software](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Classes%20-%20ok/Arquitetura%20L%C3%B3gica/Arquitetura%20L%C3%B3gica.png)
<hr>

### Diagrama de Classes - Modelo
![Diagrama de Classe - Modelo](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Classes%20-%20ok/Diagrama%20de%20Classe%20-%20Modelo/DiagramaClasses%20-%20MODELO.png)
<hr>

### Diagrama de Classes - Visão
![Diagrama de Classe - Visão](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Classes%20-%20ok/Diagrama%20de%20Classe%20-%20Vis%C3%A3o/DiagramaClasses-VISAO.png)
<hr>

### Diagrama de Classes - Controle
![Diagrama de Classe - Controle](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Classes%20-%20ok/Diagrama%20de%20Classe%20-%20Controle/DiagramaClasses-CONTROLE.png)
<hr>

### Diagrama de Sequência
- [Diagrama de Sequência - Abrir Caixa](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Sequ%C3%AAncia/Abrir%20Caixa%20-%20ok/DS-Abrir_Caixa.png)

- [Diagrama de Sequência - Efetuar Compra](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Sequ%C3%AAncia/Efetuar%20Compra%20-%20ok/DS_EfetuarCompra.png)

- [Diagrama de Sequência - Efetuar Venda](---) | Em Desenvolvimento

- [Diagrama de Sequência - Fechar Caixa](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Sequ%C3%AAncia/Fechar%20Caixa%20-%20ok/DS-Fechar_Caixa.png)

- [Diagrama de Sequência - Pagar Fornecedor](---) | Em Desenvolvimento

- [Diagrama de Sequência - Realizar Sangria](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Sequ%C3%AAncia/Realizar%20Sangria%20Caixa%20-%20ok/DS_RealizarSangriaCaixa.png)

 - [Diagrama de Sequência - Realizar Suplementação](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Sequ%C3%AAncia/Realizar%20Suprimento%20Caixa%20-%20ok/DS_RealizarSuprimentoCaixa.png)

- [Diagrama de Sequência - Receber Produtos](---) | Em Desenvolvimento

- [Diagrama de Sequência - Receber Pagamento](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Sequ%C3%AAncia/Receber%20Pagamento%20-%20ok/DS_ReceberPagamento.png)

- [Diagrama de Sequência - CRUD Funcionário](---) | Em Desenvolvimento
<hr>

### Mapeamento OO-Relacional - Modelo Lógico de Dados
![Diagrama de Classe - Modelo](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Mapeamento%20OO-Relacional/Modelo%20L%C3%B3gico.png)

## Mapeamento OO-Relacional - Modelo Físico de Dados
Caixa(PK(codigoCaixa), dataAbertura, dataFechamento, horarioAbertura, horarioFechamento, status, totalEntradas, totalSaidas, valorAbertura, valorFechamento)

Fornecedor(PK(codigoFornecedor), cep, cidade, cnpj, email, endereco, nome, responsavel, telefone, uf)

Compra(PK(codigoCompra), dataCompra, formaPagamento, valorTotal, FK(codigoFornecedor))

Convenio(PK(codigoConvenio), cnpj, desconto, email, endereco, nome, telefone)

Funcionario(PK(codigoFuncionario), cep, cidade, cpf, endereco, login, nivelAcesso, nome, salario, senha, telefone, uf)

Movimentacao(PK(codigoMovimentacao, FK(codigoCaixa)), motivo, tipo, valor)

PagamentoCompra(PK(FK(codigoCompra), parcela), valor, vencimento, status, FK(codigoCaixa))

Produto(PK(codigoProduto), categoria, dataFabricacao, dataValidade, descricao, dosagem, lote, nome, quantidade, valor)

ProdutoCompra(PK(FK(codigoCompra), FK(codigoProduto)), preco, quantidade, subtotal)

Venda(PK(codigoVenda), dataVenda, formaPagamento, valorVenda, FK(codigoCaixa), FK(codigoConvenio))

ProdutoVenda(PK(FK(codigoProduto), FK(codigoVenda)), preco, quantidade, subtotal)

