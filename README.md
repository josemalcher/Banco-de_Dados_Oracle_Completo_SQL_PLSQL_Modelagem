# Banco de Dados Oracle Completo: SQL+PLSQL+Modelagem

https://www.udemy.com/course/banco-de-dados-oracle-completo-sqlplsqlmodelagem-de-dados/

CURSO ORACLE 2024 COMPLETO - Incluindo 3 cursos: SQL PL/SQL e Modelagem de Banco de Dados - Abrangendo versões 11g a 21c

## <a name="indice">Índice</a>

1. [Seção 01: Oracle SQL - Apresentação do Curso Oracle SQL](#parte1)     
2. [Seção 02: Instalação do Oracle Database 21c XE](#parte2)     
3. [Seção 03: Download e Instalação do Oracle SQL Developer](#parte3)     
4. [Seção 04: Oracle SQL - Visão Geral do Oracle Database](#parte4)     
5. [Seção 05: Oracle SQL - Introdução ao SQL](#parte5)     
6. [Seção 06: Oracle SQL - Consultando dados utilizando o comando SQL SELECT](#parte6)     
7. [Seção 07: Oracle SQL - Restringindo e Ordenando Dados](#parte7)     
8. [Seção 08: Oracle SQL - Utilizando Funções Single Row](#parte8)     
9. [Seção 09: Oracle SQL - Utilizando Funções de Conversão e Expressões Condicionais](#parte9)     
10. [Seção 10: Oracle SQL - Agregando dados utilizando Funções de Grupo](#parte10)     
11. [Seção 11: Oracle SQL - Exibindo dados a partir de Múltiplas Tabelas](#parte11)     
12. [Seção 12: Oracle SQL - Utilizando Sub-Consultas](#parte12)     
13. [Seção 13: Oracle SQL - Operadores SET](#parte13)     
14. [Seção 14: Oracle SQL - Comandos DML Manipulando dados](#parte14)     
15. [Seção 15: Oracle SQL - Comandos DDL](#parte15)     
16. [Seção 16: Oracle SQL - Criando e Gerenciando Constraints](#parte16)     
17. [Seção 17: Oracle SQL - Criando e Gerenciando Visões](#parte17)     
18. [Seção 18: Oracle SQL - Criando e Gerenciando Sequencias](#parte18)     
19. [Seção 19: Oracle SQL - Criando e Gerenciando Índices](#parte19)     
20. [Seção 20: Oracle SQL - Criando Sinônimos](#parte20)     
21. [Seção 21: Oracle SQL - Utilizando o SQL*PLUS](#parte21)     
22. [Seção 22: Oracle PL/SQI - Apresentação do curso Oracle 19c PL/SQL Furndamentos](#parte22)     
23. [Seção 23: Oracle PL/SQL - Visão Geral do Oracle PL/SQL](#parte23)     
24. [Seção 24: Oracle PL/SQL- Bloco Anônimo](#parte24)     
25. [Seção 25: Oracle PL/SQL - Declaração de Identificadores - Variáveis e Constantes](#parte25)     
26. [Seção 26: Oracle PL/SQL - Sintaxe e Diretrizes de um Bloco PL/SQL](#parte26)     
27. [Seção 27: Oracle PL/SQL - Utilizando comandos SQL no PL/SQL](#parte27)     
28. [Seção 28: Oracle PL/SQL - Estruturas de Controle](#parte28)     
29. [Seção 29: Oracle PL/SQL - Tipos Compostos - Variável Tipo PL/SQL Record](#parte29)     
30. [Seção 30: Oracle PL/SQL - Tipos Compostos - Collections](#parte30)     
31. [Seção 31: Oracle PL/SQL - Cursor Explícito](#parte31)     
32. [Seção 32: Oracle PL/SQL - Tratamento de Exceções](#parte32)     
33. [Seção 33: Oracle PL/SQL - Procedures de Banco de Dados](#parte33)     
34. [Seção 34: Oracle PL/SQL - Funções de Banco de Dados](#parte34)     
35. [Seção 35: Oracle PL/SQL - Gerenciando Procedures e Functions](#parte35)     
36. [Seção 36: Oracle PL/SQL - Gerenciando Dependências de Objetos](#parte36)     
37. [Seção 37: Oracle PL/SQL - Debugando Procedures e Functions](#parte37)     
38. [Seção 38: Oracle PL/SQL - Packages de Banco de Dados](#parte38)     
39. [Seção 39: Oracle PL/SQL - Database DML Triggers](#parte39)     
40. [Seção 40: Modelagem de Dados - Apresentação do curso Modelagem de Banco de Dados](#parte40)     
41. [Seção 41: Modelagem de Dados - Instalação do Oracle SQL Developer Data Modeler](#parte41)     
42. [Seção 42: Modelagem de Dados -Metodologia Oracle](#parte42)     
43. [Seção 43: Modelagem de Dados - Modelagem de Dados Conceitual](#parte43)     
44. [Seção 44: Modelagem de Dados - Modelagem de Dados Avançada (Detalhada)](#parte44)     
45. [Seção 45: Modelagem de Dados - Database Design - Projeto do Banco de Dados](#parte45)     
46. [Seção 46: Modelagem de Dados - Construção](#parte46)     
47. [Seção 47: Oportunidades de Carreira utilizando Tecnologias Oracle](#parte47)     
---


## <a name="parte1">1 - Seção 01: Oracle SQL - Apresentação do Curso Oracle SQL</a>

### 1 Apresentação do curso Oracle SQL.

[recursos/Seção+2+-+Pratica+Aula+1.sql](recursos/Seção+2+-+Pratica+Aula+1.sql)

![img/1_1_bd.jpeg](img/1_1_bd.jpeg)

![img/1_2_bd.jpeg](img/1_2_bd.jpeg)


[Voltar ao Índice](#indice)

---


## <a name="parte2">2 - Seção 02: Instalação do Oracle Database 21c XE</a>



### 2 Download e Instalação do Oracle Database 21c XE

![img/image.png](img/image.png)

![img/2_2_process.png](img/2_2_process.png)


### 3 Configurando o LISTENER e o TNSNAMES - Criando e testando uma Conexão Local

[recursos/Seção+2+-+Pratica+Aula+2.sql](recursos/Seção+2+-+Pratica+Aula+2.sql)

```
C:\Users\josem>sqlplus system/oracle@xepdb1

SQL*Plus: Release 21.0.0.0.0 - Production on Thu Apr 24 15:19:30 2025
Version 21.3.0.0.0

Copyright (c) 1982, 2021, Oracle.  All rights reserved.

ERROR:
ORA-01017: invalid username/password; logon denied


Enter user-name: system
Enter password:
Last Successful login time: Thu Apr 24 2025 15:17:25 -03:00

Connected to:
Oracle Database 21c Express Edition Release 21.0.0.0.0 - Production
Version 21.3.0.0.0

SQL> select sysdate from dual;

SYSDATE
---------
24-APR-25

SQL>
```


[Voltar ao Índice](#indice)

---


## <a name="parte3">3 - Seção 03: Download e Instalação do Oracle SQL Developer</a>

### 04 Download e Instalação do Oracle SQL Developer

[recursos/Seção+3+-+Pratica+Aula+1.sql](recursos/Seção+3+-+Pratica+Aula+1.sql)


### 05 Criando uma conexão para o usuário SYS (dba) no Oracle SQL Developer

[recursos/Seção+3+-+Pratica+Aula+2.sql](recursos/Seção+3+-+Pratica+Aula+2.sql)


### 06 Criando o Usuário HR

[recursos/Seção+3+-+Aula+3+-+Cria+Usuario+HR.sql](recursos/Seção+3+-+Aula+3+-+Cria+Usuario+HR.sql)

### 07 Criando uma conexão para o usuário HR no SQL Developer

[recursos/Seção+3+-+Pratica+Aula+4.sql](recursos/Seção+3+-+Pratica+Aula+4.sql)

### 08 Criando os objetos do schema do usuário HR

[recursos/Seção+3+-+Aula+5+-+Cria+Objetos+schema+HR.sql](recursos/Seção+3+-+Aula+5+-+Cria+Objetos+schema+HR.sql)

### 09 Populando os objetos do schema do usuário HR

[recursos/Seção+3+-+Aula+6+-+Populando+Objetos+schema+HR.sql](recursos/Seção+3+-+Aula+6+-+Populando+Objetos+schema+HR.sql)

### 10 Criando Índices, inserindo comentários e outros no schema do usuário HR

[recursos/Seção+3+-+Aula+7+-+Criando+indices+e+comentarios+schema+HR.sql](recursos/Seção+3+-+Aula+7+-+Criando+indices+e+comentarios+schema+HR.sql)

[Voltar ao Índice](#indice)

---


## <a name="parte4">4 - Seção 04: Oracle SQL - Visão Geral do Oracle Database</a>

### 11. Oracle SQL - Visão Geral do Oracle Database 21c

![img/4_11_bd.jpeg](img/4_11_bd.jpeg)

![img/4_11_2_bd.jpeg](img/4_11_2_bd.jpeg)

[Voltar ao Índice](#indice)

---


## <a name="parte5">5 - Seção 05: Oracle SQL - Introdução ao SQL</a>

### 12. Oracle SQL - Introdução ao SQL

https://docs.oracle.com/en/database/index.html


#### Data Manipulation Language (DML)

- **SELECT**  
  Recupera dados de uma tabela ou vista no banco de dados.

- **INSERT**  
  Adiciona novos registros em uma tabela.

- **UPDATE**  
  Modifica registros existentes em uma tabela.

- **DELETE**  
  Remove registros de uma tabela.

- **MERGE**  
  Combina registros de duas tabelas baseando-se em condições definidas.


##### Explicação com exemplos de código SQL

1. **SELECT**:  
   O comando `SELECT` é usado para buscar dados de tabelas.  
   ```sql
   SELECT nome, idade FROM funcionarios WHERE departamento = 'Vendas';
   SELECT * FROM produtos;
   ```

2. **INSERT**:  
   Utilizado para inserir novos registros em uma tabela.  
   ```sql
   INSERT INTO funcionarios (nome, idade, departamento) VALUES ('Ana', 28, 'RH');
   INSERT INTO produtos (nome, preco) VALUES ('Celular', 1200);
   ```

3. **UPDATE**:  
   Modifica dados existentes em uma tabela.  
   ```sql
   UPDATE funcionarios SET idade = 29 WHERE nome = 'Ana';
   UPDATE produtos SET preco = 1150 WHERE nome = 'Celular';
   ```

4. **DELETE**:  
   Remove registros de uma tabela.  
   ```sql
   DELETE FROM funcionarios WHERE departamento = 'Vendas';
   DELETE FROM produtos WHERE preco > 5000;
   ```

5. **MERGE**:  
   Combina registros entre tabelas com base em condições.  
   ```sql
   MERGE INTO funcionarios destino
   USING novos_funcionarios origem
   ON destino.id = origem.id
   WHEN MATCHED THEN
       UPDATE SET destino.nome = origem.nome
   WHEN NOT MATCHED THEN
       INSERT (id, nome, idade, departamento)
       VALUES (origem.id, origem.nome, origem.idade, origem.departamento);
   ```


##### Data Definition Language (DDL)

- **CREATE**  
  Usado para criar novos objetos no banco de dados (tabelas, índices, vistas, etc.).

- **ALTER**  
  Usado para modificar a estrutura de objetos existentes no banco de dados.

- **DROP**  
  Usado para deletar objetos existentes no banco de dados.

- **RENAME**  
  Usado para renomear objetos do banco de dados.

- **TRUNCATE**  
  Usado para remover todas as linhas de uma tabela rapidamente, sem log de exclusão.

- **COMMENT**  
  Usado para adicionar comentários nos objetos do banco de dados.


##### Explicação com exemplos de código SQL

1. **CREATE**:  
   O comando `CREATE` é utilizado para criar novos objetos no banco de dados.  
   ```sql
   CREATE TABLE funcionarios (
       id INT PRIMARY KEY,
       nome VARCHAR(100),
       cargo VARCHAR(50),
       salario DECIMAL(10, 2)
   );
   ```

2. **ALTER**:  
   O comando `ALTER` modifica objetos existentes.  
   ```sql
   ALTER TABLE funcionarios ADD email VARCHAR(100);
   ALTER TABLE funcionarios DROP COLUMN email;
   ```

3. **DROP**:  
   O comando `DROP` deleta objetos do banco de dados.  
   ```sql
   DROP TABLE funcionarios;
   DROP INDEX idx_nome;
   ```

4. **RENAME**:  
   O comando `RENAME` renomeia objetos.  
   ```sql
   RENAME TABLE funcionarios TO colaboradores;
   ```

5. **TRUNCATE**:  
   O comando `TRUNCATE` remove todas as linhas de uma tabela.  
   ```sql
   TRUNCATE TABLE funcionarios;
   ```

6. **COMMENT**:  
   O comando `COMMENT` adiciona comentários nos objetos do banco de dados.  
   ```sql
   COMMENT ON TABLE funcionarios IS 'Tabela com informações sobre os funcionários';
   COMMENT ON COLUMN funcionarios.nome IS 'Nome completo do funcionário';
   ```


#### Data Control Language (DCL)

##### GRANT
- Usado para conceder permissões a usuários ou roles para acessar objetos do banco de dados.  
  **Exemplo de código SQL:**  
  ```sql
  GRANT SELECT, INSERT ON funcionarios TO usuario1;
  GRANT ALL PRIVILEGES ON tabela TO role1;
  ```

##### REVOKE
- Usado para remover permissões previamente concedidas a usuários ou roles.  
  **Exemplo de código SQL:**  
  ```sql
  REVOKE SELECT, INSERT ON funcionarios FROM usuario1;
  REVOKE ALL PRIVILEGES ON tabela FROM role1;
  ```


#### Transaction Control

- **COMMIT**
- **ROLLBACK**
- **SAVEPOINT**


#### **COMMIT**
`COMMIT` é usado para **salvar** todas as alterações feitas durante a transação no banco de dados de forma permanente.

**Exemplo SQL:**
```sql
BEGIN TRANSACTION;

INSERT INTO clientes (nome, email) VALUES ('Maria', 'maria@email.com');
UPDATE clientes SET email = 'novoemail@email.com' WHERE id = 1;

COMMIT;
```
> **Explicação:**  
> Depois do `COMMIT`, as alterações ficam permanentes no banco de dados.

---

#### **ROLLBACK**
`ROLLBACK` é usado para **desfazer** todas as alterações feitas na transação atual, voltando o banco de dados ao estado anterior ao início da transação.

**Exemplo SQL:**
```sql
BEGIN TRANSACTION;

DELETE FROM clientes WHERE id = 2;

-- Opa, percebemos que o ID estava errado
ROLLBACK;
```
> **Explicação:**  
> O `ROLLBACK` cancela a exclusão do cliente, como se a operação nunca tivesse ocorrido.

---

#### **SAVEPOINT**
`SAVEPOINT` cria um **ponto de salvamento** dentro de uma transação, permitindo que você faça um `ROLLBACK` apenas até esse ponto, sem cancelar toda a transação.

**Exemplo SQL:**
```sql
BEGIN TRANSACTION;

INSERT INTO pedidos (produto, quantidade) VALUES ('Notebook', 1);
SAVEPOINT ponto1;

INSERT INTO pedidos (produto, quantidade) VALUES ('Teclado', 2);

-- Algo deu errado na segunda inserção
ROLLBACK TO ponto1;

COMMIT;
```
> **Explicação:**  
> Usamos `SAVEPOINT` para marcar um momento seguro. Se houver erro depois dele, o `ROLLBACK TO` retorna até aquele ponto, e não até o início da transação.

---

### 🧠 Dicas de Melhores Práticas:
- Sempre use `COMMIT` apenas quando tiver certeza de que todos os dados foram manipulados corretamente.
- Use `SAVEPOINT` para operações mais delicadas, onde erros parciais podem ocorrer.
- Após um `ROLLBACK`, revise o que aconteceu antes de tentar a operação de novo.




[Voltar ao Índice](#indice)

---


## <a name="parte6">6 - Seção 06: Oracle SQL - Consultando dados utilizando o comando SQL SELECT</a>

### 13. Oracle SQL - Consultando dados utilizando o comando SQL SELECT

- [recursos/Seção+6+-+Prática+Aula+1.sql](recursos/Seção+6+-+Prática+Aula+1.sql)

![alt text](img/13_1.png)


#### Escrevendo comandos SQL

- Comandos SQL não são case sensitivos
- Comandos SQL podem se estender por uma ou mais linhas
- Palavras-chave (Keywords) não podem ser abreviadas ou divididas através das linhas
- Cláusulas são normalmente colocadas em linhas separadas
- Indentações são utilizadas para facilitar o entendimento do comando
- Comandos SQL são terminados por ponto e vírgula (;)


#### Alinhamento de colunas em cabeçalhos

- **Colunas Character e Date**  
  Alinhamento default do cabeçalho: Esquerda
- **Colunas Number**  
  Alinhamento default do cabeçalho: Direita
- **Exibição default do cabeçalho**: Letras Maiúsculas

#### Regras de Precedência de Operadores

Mesmas regras de precedência da matemática:
1. Identidade (Positivo ou Negativo).
2. Multiplicação e Divisão: possuem a mesma precedência, resolvendo da esquerda para a direita.
3. Soma e Subtração: possuem a mesma precedência, resolvendo da esquerda para a direita.

#### Entendo o valor Nulo (NULL)

- Null é ausência de valor.
- Null não é zero.
- Null não é espaços em branco.
- Null não é zeros binários.

#### Utilizando Valores Nulos em Expressões Aritméticas

- **Qualquer expressão aritmética utilizando NULL retorna NULL.**

```sql
SELECT  first_name, last_name, job_id, commission_pct, 200000 * commission_pct
FROM    employees
WHERE   commission_pct IS NULL;


FIRST_NAME           LAST_NAME                 JOB_ID     COMMISSION_PCT 200000*COMMISSION_PCT
-------------------- ------------------------- ---------- -------------- ---------------------
Donald               OConnell                  SH_CLERK                                       
Douglas              Grant                     SH_CLERK                                       
Jennifer             Whalen                    AD_ASST                                        
Michael              Hartstein                 MK_MAN                                         
Pat                  Fay                       MK_REP                                         
Susan                Mavris                    HR_REP                                         
Hermann              Baer                      PR_REP                                         
Shelley              Higgins                   AC_MGR                                         
William              Gietz                     AC_ACCOUNT                                     
Steven               King                      AD_PRES                                        
Neena                Kochhar                   AD_VP                                          
```

#### Alias de Coluna

- Renomeia o cabeçalho da coluna.
- Segue imediatamente o nome da coluna.
- Opcionalmente pode ser utilizada a palavra-chave **AS** entre a coluna e o alias.
- Quando o alias contém espaços, caracteres especiais ou for case sensitive (letras minúsculas), então deve ser colocado entre aspas duplas (").

```sql
SELECT first_name "Nome", last_name "Sobrenome", salary "Salário ($)", commission_pct "Percentual de comissão"
FROM   employees;


Nome                 Sobrenome                 Salário ($) Percentual de comissão
-------------------- ------------------------- ----------- ----------------------
Donald               OConnell                         2600                       
Douglas              Grant                            2600                       
Jennifer             Whalen                           4400                       
Michael              Hartstein                       13000                       
```

#### Operador de concatenação

- Liga colunas ou strings de caracteres com outras colunas ou strings de caracteres.
- É representado por duas barras verticais (||).
- Cria uma coluna resultante da ligação que é um string de caracteres.

```sql
SELECT first_name || ' ' || last_name || ', data de admissão: ' || hire_date "Funcionário"
FROM   employees;


Funcionário                                                                         
------------------------------------------------------------------------------------
Lisa Ozer, data de admissão: 11-MAR-05
Harrison Bloom, data de admissão: 23-MAR-06
Tayler Fox, data de admissão: 24-JAN-06
William Smith, data de admissão: 23-FEB-07
Elizabeth Bates, data de admissão: 24-MAR-07
Sundita Kumar, data de admissão: 21-APR-08
Ellen Abel, data de admissão: 11-MAY-04
Alyssa Hutton, data de admissão: 19-MAR-05
Jonathon Taylor, data de admissão: 24-MAR-06
Jack Livingston, data de admissão: 23-APR-06
Kimberely Grant, data de admissão: 24-MAY-07
```
#### Strings de caracteres

- Um literal é um caracter, um número, ou uma string que é incluída em um comando SELECT.
- Literais de Datas e caracteres devem ser definidos entre aspas simples (`'`).
- Cada literal ou string de caracteres será exibido uma vez para cada linha retornada.

#### Operador alternativo para aspas

- Você pode especificar seu próprio operador alternativo para aspas.
- Escolha qualquer delimitador.
- Facilita a legibilidade e usabilidade.

```sql
SELECT department_name || q'[ Department's Manager Id: ]'
|| manager_id "Departamento e Gerente"
FROM departments;


Departamento e Gerente                                                                          
------------------------------------------------------------------------------------------------
Administration Department's Manager Id: 200
Marketing Department's Manager Id: 201
Purchasing Department's Manager Id: 114
Human Resources Department's Manager Id: 203
Shipping Department's Manager Id: 121
IT Department's Manager Id: 103
Public Relations Department's Manager Id: 204
Sales Department's Manager Id: 145
Executive Department's Manager Id: 100
Finance Department's Manager Id: 108
Accounting Department's Manager Id: 205
```

#### Linhas duplicadas

- Por default as consultas exibem todas as linhas retornadas, incluindo as linhas duplicadas.

```sql
-- Linhas duplicadas
SELECT department_id
FROM employees;

DEPARTMENT_ID
-------------
           50
           50
           10
           20
           20
           40
           70

-- Utilizando DISTINCT para eliminar linhas duplicadas

SELECT DISTINCT department_id
FROM employees;


DEPARTMENT_ID
-------------
           50
           10
           20
           40
           70
          110
           90
           60
          100
           30
           80
```

[Voltar ao Índice](#indice)

---


## <a name="parte7">7 - Seção 07: Oracle SQL - Restringindo e Ordenando Dados</a>

### 14. Oracle SQL - Restringindo e Ordenando Dados



[Voltar ao Índice](#indice)

---


## <a name="parte8">8 - Seção 08: Oracle SQL - Utilizando Funções Single Row</a>



[Voltar ao Índice](#indice)

---


## <a name="parte9">9 - Seção 09: Oracle SQL - Utilizando Funções de Conversão e Expressões Condicionais</a>



[Voltar ao Índice](#indice)

---


## <a name="parte10">10 - Seção 10: Oracle SQL - Agregando dados utilizando Funções de Grupo</a>



[Voltar ao Índice](#indice)

---


## <a name="parte11">11 - Seção 11: Oracle SQL - Exibindo dados a partir de Múltiplas Tabelas</a>



[Voltar ao Índice](#indice)

---


## <a name="parte12">12 - Seção 12: Oracle SQL - Utilizando Sub-Consultas</a>



[Voltar ao Índice](#indice)

---


## <a name="parte13">13 - Seção 13: Oracle SQL - Operadores SET</a>



[Voltar ao Índice](#indice)

---


## <a name="parte14">14 - Seção 14: Oracle SQL - Comandos DML Manipulando dados</a>



[Voltar ao Índice](#indice)

---


## <a name="parte15">15 - Seção 15: Oracle SQL - Comandos DDL</a>



[Voltar ao Índice](#indice)

---


## <a name="parte16">16 - Seção 16: Oracle SQL - Criando e Gerenciando Constraints</a>



[Voltar ao Índice](#indice)

---


## <a name="parte17">17 - Seção 17: Oracle SQL - Criando e Gerenciando Visões</a>



[Voltar ao Índice](#indice)

---


## <a name="parte18">18 - Seção 18: Oracle SQL - Criando e Gerenciando Sequencias</a>



[Voltar ao Índice](#indice)

---


## <a name="parte19">19 - Seção 19: Oracle SQL - Criando e Gerenciando Índices</a>



[Voltar ao Índice](#indice)

---


## <a name="parte20">20 - Seção 20: Oracle SQL - Criando Sinônimos</a>



[Voltar ao Índice](#indice)

---


## <a name="parte21">21 - Seção 21: Oracle SQL - Utilizando o SQL*PLUS</a>



[Voltar ao Índice](#indice)

---


## <a name="parte22">22 - Seção 22: Oracle PL/SQI - Apresentação do curso Oracle 19c PL/SQL Furndamentos</a>



[Voltar ao Índice](#indice)

---


## <a name="parte23">23 - Seção 23: Oracle PL/SQL - Visão Geral do Oracle PL/SQL</a>



[Voltar ao Índice](#indice)

---


## <a name="parte24">24 - Seção 24: Oracle PL/SQL- Bloco Anônimo</a>



[Voltar ao Índice](#indice)

---


## <a name="parte25">25 - Seção 25: Oracle PL/SQL - Declaração de Identificadores - Variáveis e Constantes</a>



[Voltar ao Índice](#indice)

---


## <a name="parte26">26 - Seção 26: Oracle PL/SQL - Sintaxe e Diretrizes de um Bloco PL/SQL</a>



[Voltar ao Índice](#indice)

---


## <a name="parte27">27 - Seção 27: Oracle PL/SQL - Utilizando comandos SQL no PL/SQL</a>



[Voltar ao Índice](#indice)

---


## <a name="parte28">28 - Seção 28: Oracle PL/SQL - Estruturas de Controle</a>



[Voltar ao Índice](#indice)

---


## <a name="parte29">29 - Seção 29: Oracle PL/SQL - Tipos Compostos - Variável Tipo PL/SQL Record</a>



[Voltar ao Índice](#indice)

---


## <a name="parte30">30 - Seção 30: Oracle PL/SQL - Tipos Compostos - Collections</a>



[Voltar ao Índice](#indice)

---


## <a name="parte31">31 - Seção 31: Oracle PL/SQL - Cursor Explícito</a>



[Voltar ao Índice](#indice)

---


## <a name="parte32">32 - Seção 32: Oracle PL/SQL - Tratamento de Exceções</a>



[Voltar ao Índice](#indice)

---


## <a name="parte33">33 - Seção 33: Oracle PL/SQL - Procedures de Banco de Dados</a>



[Voltar ao Índice](#indice)

---


## <a name="parte34">34 - Seção 34: Oracle PL/SQL - Funções de Banco de Dados</a>



[Voltar ao Índice](#indice)

---


## <a name="parte35">35 - Seção 35: Oracle PL/SQL - Gerenciando Procedures e Functions</a>



[Voltar ao Índice](#indice)

---


## <a name="parte36">36 - Seção 36: Oracle PL/SQL - Gerenciando Dependências de Objetos</a>



[Voltar ao Índice](#indice)

---


## <a name="parte37">37 - Seção 37: Oracle PL/SQL - Debugando Procedures e Functions</a>



[Voltar ao Índice](#indice)

---


## <a name="parte38">38 - Seção 38: Oracle PL/SQL - Packages de Banco de Dados</a>



[Voltar ao Índice](#indice)

---


## <a name="parte39">39 - Seção 39: Oracle PL/SQL - Database DML Triggers</a>



[Voltar ao Índice](#indice)

---


## <a name="parte40">40 - Seção 40: Modelagem de Dados - Apresentação do curso Modelagem de Banco de Dados</a>



[Voltar ao Índice](#indice)

---


## <a name="parte41">41 - Seção 41: Modelagem de Dados - Instalação do Oracle SQL Developer Data Modeler</a>



[Voltar ao Índice](#indice)

---


## <a name="parte42">42 - Seção 42: Modelagem de Dados -Metodologia Oracle</a>



[Voltar ao Índice](#indice)

---


## <a name="parte43">43 - Seção 43: Modelagem de Dados - Modelagem de Dados Conceitual</a>



[Voltar ao Índice](#indice)

---


## <a name="parte44">44 - Seção 44: Modelagem de Dados - Modelagem de Dados Avançada (Detalhada)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte45">45 - Seção 45: Modelagem de Dados - Database Design - Projeto do Banco de Dados</a>



[Voltar ao Índice](#indice)

---


## <a name="parte46">46 - Seção 46: Modelagem de Dados - Construção</a>



[Voltar ao Índice](#indice)

---


## <a name="parte47">47 - Seção 47: Oportunidades de Carreira utilizando Tecnologias Oracle</a>



[Voltar ao Índice](#indice)

---

