# **Índice**

- Descrição do Projeto
- Instalação
- Modelagem do Sistema
- Modelagem do Banco de Dados
- Licença
- Contato


# **PROJETO RELOJOARIA**
---

## Descrição do Projeto

 Esse projeto é um sistema de uma loja de relogios, que visa trazer facilidade de funcionalidade para o funcionário
  e mais facilidade de acessar o banco de estoque e preço dos produtos.
  Também para facilitar no cadastro de clientes e funcionários, trazendo integridade aos dados de todos.

---

## Instalação

### Pré-requisitos

- Python (versão 3.10 ou superior)
- pip instal ttkbootstrap
- mysql-connector
- Banco de dados MySQL

---

## Modelagem de Sistema
Abaixo está os modelos de diagrama de sistema.

**Diagrama Caso de Uso**
---
![Caso de Uso](https://github.com/Sarahlemonede09/PROJETO-RELOJOARIA/blob/main/DIAGRAMA-CASO-DE-USO.png)

**Diagrama de Sequência**
---
![Diagrama de Sequencia](https://github.com/Sarahlemonede09/PROJETO-RELOJOARIA/blob/main/DIAGRAMA-DE-SEQUENCIA.png)

## Modelagem do Banco de Dados
Abaixo está os modelos de banco de dados.

**Modelo conceitual**
---
![Modelo conceitual](https://github.com/SarahLemos/PROJECT-ONE--Relojoaria./blob/main/MODELO-CONCEITUAL.BD.png)

**Modelo Físico**
---
![Modelo Físico](https://github.com/SarahLemos/PROJECT-ONE--Relojoaria./blob/main/TABELA-FISICA.BD.png)

---

## Estrutura das Tabelas

**Tabela `relojoaria`**

 - **id (PK)**: Identificador único da loja.


- **nome**: Nome completo da intituição.


- **cnpj**: Cadastro Nacional da Pessoa Jurídica (loja)


- **endereço**: local onde a loja fica.



 **Tabela `Funcionário`**

- **id (PK)**: Identificador único do funcionário(matricula).


- **nome**: identificação do funcionário.


- **cpf**: conprovante de pessoa fisica do funcionário.


- **função**: função do funcionário (caixa, vendedor, gerente)


- **telefone**: contato do funcionário.


- **email**: email para contato profissional.



 **Tabela `Cadastro de Cliente`**



- **id (PK)**: Identificador único da cliente cadastrado.


- **nome**: Nome do cliente.


- **id(FK)**: Identificador da onde vai ser salvo o cadastro.


- **cpf**: comprovante de pessoa física do cliente.


- **endereço**: endereço para comprovar local de entrega se necessário do cliente.


- **email**: email para envio de boletos, confirmação de compras e promoções.


- **telcell**: telefone ou celular do cliente para contato com o próprio.



**Tabela `Venda`**



- **id (PK)**: Identificador único da venda.


- **quant_prod**: quantiadde de produtos vendidos.


- **id (FK)**: identificador de onde vai ser lançado as informações.


- **valor_unit**: valor unitári de cada produto.


- **valor_tot**: valor total da venda.



**Tabela `Produto`**



- **id(PK)**: identificador único do  produto.


- **nome**: nome do produto.


- **id(FK)**: identificador de onde as informações serão lançadas.


- **tipo**: tipo do produto.


- **marca**: marca do produto.


- **valor_unid**: valor da unidade do produto.


- **modelo**: modelo do produto.


- **material**: tipo de material utilizado da fabricação.



**Tabela `Estoque`**



- **id(PK)**: indentificador único do estoque.


- **quant_armazenado**: quantidade total armazenada no estoque.


- **id(FK)**: identicador de onde as informações dos produtos vão vir.



---

## Licença

Este projeto é licenciado sob a Licença MIT.

## Contato

Desenvolvido por **Sarah Gabriela Lemos, Isaque Klehm, Felipe de Lima e Gabriel Casagrande**. 
