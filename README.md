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
![Diagrama de Caso de Uso](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20Caso%20de%20Uso/DCU-Principal.png)

<hr>

## Especificação Textual dos Casos de Uso

- **Caso: Efetuar Venda**  
  Especificação: [Efetuar Venda](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Efetuar%20Venda/Especifica%C3%A7%C3%A3o%20Textual%20%5BEfetuar%20Venda%5D.txt)
  
- **Caso: Abrir Caixa**  
  Especificação: [Abrir Caixa](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Abrir%20Caixa/Especifica%C3%A7%C3%A3o%20Textual%20%5BAbrir%20Caixa%5D.txt)

- **Caso: Fechar Caixa**  
  Especificação: [Fechar Caixa](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Fechar%20Caixa/Especifica%C3%A7%C3%A3o%20Textual%20%5BFechar%20Caixa%5D.txt)

- **Caso: Efetuar Sangria**  
  Especificação: [Efetuar Sangria](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Realizar%20Sangria%20Caixa/Especifica%C3%A7%C3%A3o%20Textual%20%5BRealizar%20Sangria%5D.txt)

- **Caso: Efetuar Suplementação**  
  Especificação: [Efetuar Suplementação](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Realizar%20Suprimento%20Caixa/Especifica%C3%A7%C3%A3o%20Textual%20%5BSuplementa%C3%A7%C3%A3o%20Caixa%5D.txt)

- **Caso: Efetuar Compra**  
  Especificação: [Efetuar Compra](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Efetuar%20Compra/Especifica%C3%A7%C3%A3o%20Textual%20%5BEfetuar%20Compra%5D.txt)

- **Caso: Pagar Fornecedor**  
  Especificação: [Pagar Fornecedor](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Pagar%20Fornecedor/Especifica%C3%A7%C3%A3o%20Textual%20%5BPagar%20Fornecedor%5D.txt)

- **Caso: Receber Produto**  
  Especificação: [Receber Produto](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Receber%20Produtos/Especifica%C3%A7%C3%A3o%20Textual%20%5BReceber%20Produtos%5D.txt)

- **Caso: Receber Pagamento**  
  Especificação: [Em Desenvolvimento...](google.com)

- **Caso: Manter Funcionário (CRUD)**  
  Especificação: [CRUD Funcionário](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Manter%20Funcion%C3%A1rio/Especifica%C3%A7%C3%A3o%20Textual%20%5BCRUD%20Funcion%C3%A1rio%5D.txt)

### Diagramas de Atividade

- [Diagrama de Atividade - Abrir Caixa](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Abrir%20Caixa/DEA-Abrir_Caixa.png)

- [Diagrama de Atividade - Fechar Caixa](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Fechar%20Caixa/DEA_Fechar_Caixa.png)

- [Diagrama de Atividade - Efetuar Compra](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Efetuar%20Compra/DEA_EfetuarCompra.png)

- [Diagrama de Atividade - Efetuar Venda](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Efetuar%20Venda/DEA_EfetuarVenda.png)

- [Diagrama de Atividade - Pagar Fornecedor](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Pagar%20Fornecedor/DEA_PagarFornecedor.png)

- [Diagrama de Atividade - Realizar Sangria](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Realizar%20Sangria%20Caixa/DEA_RealizarSangriaCaixa.png)

 - [Diagrama de Atividade - Realizar Suplementação](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Realizar%20Suprimento%20Caixa/DEA_RealizarSuprimentoCaixa.png)

- [Diagrama de Atividade - Receber Produtos](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Receber%20Produtos/DEA_ReceberProdutos.png)

- [Diagrama de Atividade - Receber Pagamento](google.com)
  
### CRUD Funcionário
- [Diagrama de Atividade - CRUD Funcionário Inserir](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Manter%20Funcion%C3%A1rio/DA-Incluir%20Funcion%C3%A1rio.png)
- [Diagrama de Atividade - CRUD Funcionário Alterar](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Manter%20Funcion%C3%A1rio/DA-Editar%20Funcion%C3%A1rio.png)
- [Diagrama de Atividade - CRUD Funcionário Remover](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Manter%20Funcion%C3%A1rio/DA-Excluir%20Funcion%C3%A1rio.png)
- [Diagrama de Atividade - CRUD Funcionário Consultar](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Atividade/Manter%20Funcion%C3%A1rio/DA-Visualizar%20Funcion%C3%A1rio.png)
<hr>

# Capítulo 5 - Projeto de Software
### Arquitetura Lógica de Software
![Arqutietura Lógica de Software](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Classes/Arquitetura%20L%C3%B3gica/Arquitetura%20L%C3%B3gica.png)
<hr>

### Diagrama de Classes - Modelo
![Diagrama de Classe - Modelo](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Classes/Diagrama%20de%20Classe%20-%20Modelo/DiagramaClasses%20-%20MODELO.png)
<hr>

### Diagrama de Classes - Visão
![Diagrama de Classe - Visão](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Classes/Diagrama%20de%20Classe%20-%20Vis%C3%A3o/DiagramaClasses-VISAO.png)
<hr>

### Diagrama de Classes - Controle
![Diagrama de Classe - Controle](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Diagrama%20de%20Classes/Diagrama%20de%20Classe%20-%20Controle/DiagramaClasses-CONTROLEDAO.png)
<hr>

### Diagrama de Sequência - (Nome do Diagrama de Sequencia)
- [Diagrama de Sequência - Abrir Caixa](---)

- [Diagrama de Sequência - Fechar Caixa](---)

- [Diagrama de Sequência - Efetuar Compra](---)

- [Diagrama de Sequência - Efetuar Venda](---)

- [Diagrama de Sequência - Pagar Fornecedor](---)

- [Diagrama de Sequência - Realizar Sangria](---)

 - [Diagrama de Sequência - Realizar Suplementação](---)

- [Diagrama de Sequência - Receber Produtos](---)

- [Diagrama de Sequência - Receber Pagamento](---)

- [Diagrama de Sequência - CRUD Funcionário](---)
<hr>

### Mapeamento OO-Relacional - Modelo Lógico de Dados
![Diagrama de Classe - Modelo](https://github.com/Xandyssz/Projeto-Integrador-2--APS--FP1--BD2-/blob/main/Mapeamento%20OO-Relacional/Modelo%20L%C3%B3gico.png)

