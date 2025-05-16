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

- [recursos/Seção+7+-+Prática+Aula+1.sql](/recursos/Seção+7+-+Prática+Aula+1.sql)

#### Restringindo as linhas que serão retornadas

- Selecione as linhas que serão retornadas utilizando a cláusula `WHERE`

A cláusula `WHERE` é usada para **filtrar registros** que satisfazem uma condição específica. Apenas as linhas que atendem ao critério da cláusula `WHERE` serão incluídas no resultado da consulta.

---

### 📌 Exemplos de uso da cláusula `WHERE`

#### 1. Selecionar clientes de um país específico

```sql
SELECT * FROM clientes
WHERE pais = 'Brasil';
```

Esse comando retorna todos os clientes cujo país seja "Brasil".

---

#### 2. Filtrar produtos com preço maior que 100

```sql
SELECT nome, preco FROM produtos
WHERE preco > 100;
```

Retorna o nome e preço dos produtos que custam mais de R$ 100.

---

#### 3. Buscar funcionários com salário entre 3000 e 6000

```sql
SELECT nome, salario FROM funcionarios
WHERE salario BETWEEN 3000 AND 6000;
```

Usa `BETWEEN` para retornar funcionários com salários dentro desse intervalo.

---

#### 4. Encontrar pedidos feitos após uma certa data

```sql
SELECT * FROM pedidos
WHERE data_pedido > '2024-01-01';
```

Retorna todos os pedidos realizados após 1º de janeiro de 2024.

---

#### 5. Buscar nomes que começam com a letra "A"

```sql
SELECT nome FROM usuarios
WHERE nome LIKE 'A%';
```

Utiliza `LIKE` com o caractere curinga `%` para encontrar nomes que começam com "A".

---

### ✅ Boas práticas

- Utilize índices nas colunas frequentemente usadas em cláusulas `WHERE` para melhorar o desempenho.
- Evite funções nas colunas da cláusula `WHERE` quando possível, pois isso pode desativar o uso de índices.
- Prefira operadores como `BETWEEN`, `IN`, `LIKE` com cuidado para manter a legibilidade e performance.

---

### ⚠️ Evitar

- Evite escrever condições vagas ou sem filtro, como `WHERE 1=1`, pois isso pode resultar em consultas ineficientes ou até perigosas.
- Não confunda `=` com `LIKE` ou `IN` — cada um tem seu propósito específico para filtragem.

---

#### Strings de caractere e datas

- **Strings de caracteres e datas são delimitados por aspas simples (`'`)**

  Em SQL, qualquer valor literal de texto ou data precisa estar entre aspas simples.

  **Exemplo:**
  ```sql
  SELECT * FROM produtos WHERE nome = 'Teclado';
  SELECT * FROM pedidos WHERE data_pedido = '2024-04-29';
  ```

---

- **Valores de strings de caracteres são case sensitive**

  Comparações de strings em muitos bancos de dados (como PostgreSQL e Oracle) diferenciam letras maiúsculas de minúsculas.

  **Exemplo:**
  ```sql
  SELECT * FROM usuarios WHERE nome = 'João';  -- diferente de 'joão'
  ```

  > 🔍 Observação: em bancos como MySQL, a sensibilidade a maiúsculas/minúsculas pode depender do collation da tabela/coluna (`utf8_general_ci` ignora maiúsculas).

---

- **Valores de strings de data são sensíveis ao formato definido para o banco de dados ou para a sessão**

  Isso significa que a forma como as datas são inseridas ou comparadas deve respeitar o formato de data vigente.

  **Exemplo:**
  ```sql
  SELECT * FROM vendas WHERE data_venda = TO_DATE('29/04/2024', 'DD/MM/YYYY');
  ```

  Em Oracle, por exemplo, a função `TO_DATE` permite especificar o formato. Outros bancos, como PostgreSQL ou MySQL, também podem exigir formatações específicas ou utilizar funções próprias para manipulação de datas.

---

- **O formato default para exibição de datas mais utilizado no Brasil é ‘DD/MM/YY’ ou ‘DD/MM/RR’**

  - `DD` = Dia
  - `MM` = Mês
  - `YY` ou `RR` = Ano com dois dígitos

  **Exemplo:**
  ```sql
  SELECT TO_CHAR(SYSDATE, 'DD/MM/YY') FROM dual;  -- Oracle
  SELECT DATE_FORMAT(NOW(), '%d/%m/%y');          -- MySQL
  ```

  O formato pode ser configurado na sessão ou definido como padrão pelo banco.

---

### ✅ Boas práticas

- Sempre use `TO_DATE()` (Oracle) ou `DATE_FORMAT()`/`STR_TO_DATE()` (MySQL) para evitar ambiguidades.
- Mantenha consistência no formato de datas em toda a aplicação.
- Utilize `UPPER()` ou `LOWER()` se quiser evitar problemas com case sensitivity em strings.

### ⚠️ Evitar

- Não esquecer de usar aspas simples em valores literais.
- Evitar misturar formatos de datas em diferentes partes do código.
- Não confiar no comportamento "default" do banco sem confirmar a configuração de localidade (NLS, locale, etc).

#### Operadores de comparação

| Operator        | Meaning                            |
|----------------|------------------------------------|
| =              | Equal to                           |
| >              | Greater than                       |
| >=             | Greater than or equal to           |
| <              | Less than                          |
| <=             | Less than or equal to              |
| <>             | Not equal to                       |
| BETWEEN ...AND... | Between two values (inclusive)  |
| IN(set)        | Match any of a list of values      |
| LIKE           | Match a character pattern          |
| IS NULL        | Is a null value                    |



#### Selecionando valores por coincidência com padrões utilizando o operador LIKE

- Use o operador LIKE para executar pesquisas de valores que coincidem com padrões utilizando caracteres curingas (wildcards).
- As Condições de pesquisa podem conter caracteres ou números:
  - `%` Combina com zero ou mais caracteres
  - `_` Combina com um e somente um caractere

---

### Explicação com exemplos em Oracle SQL

#### 1. **LIKE com o caractere `%`**
O caractere `%` é utilizado para corresponder a **zero ou mais caracteres**. Muito útil para localizar palavras com início, meio ou fim conhecido.

**Exemplo:**
```sql
SELECT * FROM clientes
WHERE nome LIKE 'Mar%';
```
*Seleciona todos os clientes cujo nome começa com "Mar", como "Maria", "Marcos", "Martins".*

#### 2. **LIKE com o caractere `_`**
O caractere `_` substitui **apenas um caractere**. Ideal quando você quer buscar por valores com comprimento fixo ou variação mínima.

**Exemplo:**
```sql
SELECT * FROM produtos
WHERE codigo LIKE 'A_1';
```
*Seleciona todos os produtos cujo código tenha três caracteres e comece com "A", seguido de qualquer um caractere, e termine com "1".*

#### 3. **Combinação dos curingas**
Você também pode combinar `%` e `_` para pesquisas mais refinadas.

**Exemplo:**
```sql
SELECT * FROM funcionarios
WHERE cargo LIKE '_anal%';
```
*Busca cargos que tenham um caractere antes de "anal" e qualquer quantidade de caracteres depois, como "Analista", "canalizador", etc.*

---

#### Comparações com valor NULO (NULL)

- Qualquer comparação com valor NULL retorna o booleano NULL
- **Para podermos verificar se um valor é NULL deve ser utilizado a expressão IS NULL**

---

### Explicações e Exemplos em Oracle SQL

#### 1. **Comparações com NULL não funcionam com operadores tradicionais**

No Oracle (e em SQL no geral), valores `NULL` representam **desconhecido**, então qualquer operação com `NULL` resulta em `NULL` (não verdadeiro nem falso).

**Errado:**
```sql
SELECT * FROM funcionarios
WHERE salario = NULL;
```
*Esse comando não retorna nada, porque `salario = NULL` nunca será verdadeiro.*

---

#### 2. **Forma correta: `IS NULL` e `IS NOT NULL`**

Use `IS NULL` para verificar se um campo **não possui valor**.

**Exemplo com `IS NULL`:**
```sql
SELECT * FROM funcionarios
WHERE comissao IS NULL;
```
*Retorna funcionários que **não recebem comissão**.*

**Exemplo com `IS NOT NULL`:**
```sql
SELECT * FROM funcionarios
WHERE comissao IS NOT NULL;
```
*Retorna funcionários que **recebem alguma comissão**.*

---

#### Definindo Condições utilizando Operadores Lógicos

- **AND** – Retorna TRUE se ambas as condições são verdadeiras
- **OR** – Retorna TRUE se pelo menos uma das condições for verdadeira
- **NOT** – Retorna a negação da condição.  
  - Retorna TRUE se a condição é falsa  
  - Retorna FALSE se a condição é verdadeira  
  - Retorna NULL se a condição é NULL

---

### Explicações com exemplos em Oracle SQL

#### 🔹 **AND**

Usado quando **todas** as condições devem ser verdadeiras para retornar um resultado.

**Exemplo:**
```sql
SELECT * FROM funcionarios
WHERE departamento_id = 10
AND salario > 3000;
```
*Seleciona funcionários do departamento 10 que recebem mais de 3000.*

---

#### 🔹 **OR**

Usado quando **pelo menos uma** condição deve ser verdadeira.

**Exemplo:**
```sql
SELECT * FROM funcionarios
WHERE departamento_id = 10
OR salario > 3000;
```
*Seleciona funcionários do departamento 10 **ou** que recebem mais de 3000.*

---

#### 🔹 **NOT**

Usado para **negar** uma condição lógica.

**Exemplo:**
```sql
SELECT * FROM funcionarios
WHERE NOT (departamento_id = 10);
```
*Seleciona todos os funcionários **exceto** os do departamento 10.*

---

### Observação sobre NULL com NOT

Quando se usa `NOT` com uma expressão que retorna `NULL`, o resultado continua sendo `NULL`. Exemplo:

```sql
SELECT * FROM funcionarios
WHERE NOT (comissao IS NULL);
```
*Seleciona todos os funcionários **que possuem comissão**, pois `IS NULL` retorna TRUE apenas quando o valor é de fato nulo.*

---

#### Regras de Precedência

1. Operadores aritméticos  
2. Operador de concatenação  
3. Condições de comparação  
4. IS [NOT] NULL, LIKE, [NOT] IN  
5. [NOT] BETWEEN  
6. NOT EQUAL TO  
7. NOT condição lógica  
8. AND condição lógica  
9. OR condição lógica

---

### 📘 Explicações e Exemplos SQL (Oracle)

#### 1. **Operadores aritméticos**
Executam cálculos matemáticos primeiro.

```sql
SELECT nome, salario + salario * 0.10 AS novo_salario
FROM funcionarios;
```
*Aumenta o salário em 10% usando operadores aritméticos.*

---

#### 2. **Operador de concatenação (`||`)**
Concatena duas ou mais strings.

```sql
SELECT nome || ' - ' || cargo AS descricao
FROM funcionarios;
```
*Concatena o nome e o cargo do funcionário.*

---

#### 3. **Condições de comparação (`=`, `<`, `>`, `<=`, `>=`, `<>`)**

```sql
SELECT * FROM funcionarios
WHERE salario >= 3000;
```
*Filtra funcionários com salário maior ou igual a 3000.*

---

#### 4. **`IS [NOT] NULL`, `LIKE`, `[NOT] IN`**

```sql
-- IS NULL
SELECT * FROM funcionarios WHERE comissao IS NULL;

-- LIKE
SELECT * FROM funcionarios WHERE nome LIKE 'J%';

-- IN
SELECT * FROM funcionarios WHERE departamento_id IN (10, 20, 30);
```

---

#### 5. **`[NOT] BETWEEN`**

```sql
SELECT * FROM funcionarios
WHERE salario BETWEEN 2000 AND 5000;
```
*Seleciona funcionários com salário entre 2000 e 5000 (inclusive).*

---

#### 6. **NOT EQUAL TO (`<>`)**

```sql
SELECT * FROM funcionarios
WHERE cargo <> 'Gerente';
```
*Seleciona todos os funcionários que não são Gerentes.*

---

#### 7. **NOT (condição lógica)**

```sql
SELECT * FROM funcionarios
WHERE NOT (departamento_id = 10);
```
*Seleciona funcionários que **não** estão no departamento 10.*

---

#### 8. **AND (condição lógica)**

```sql
SELECT * FROM funcionarios
WHERE salario > 2000 AND cargo = 'Analista';
```
*Ambas as condições precisam ser verdadeiras.*

---

#### 9. **OR (condição lógica)**

```sql
SELECT * FROM funcionarios
WHERE salario > 5000 OR cargo = 'Diretor';
```
*Apenas uma das condições precisa ser verdadeira.*


Essas regras de precedência são importantes para garantir que as expressões sejam avaliadas na ordem correta, evitando erros de lógica nas consultas.

---

#### Utilizando a cláusula ORDER BY

- Ordene as linhas recuperadas utilizando a cláusula ORDER BY:
  – ASC: Ordem ascendente, default
  – DESC: Ordem descendente
- A cláusula ORDER BY é a última no comando SELECT


---

### 📘 Explicações com Exemplos em Oracle SQL

#### 🔹 `ORDER BY`

A cláusula `ORDER BY` é usada para classificar os registros retornados por uma consulta.

---

#### 🟢 `ASC` – Ordem Ascendente (padrão)

Ordena os resultados do menor para o maior (A-Z ou 0-9).

```sql
SELECT nome, salario
FROM funcionarios
ORDER BY salario ASC;
```

> Ordena os funcionários do menor para o maior salário.

---

#### 🔴 `DESC` – Ordem Descendente

Ordena os resultados do maior para o menor (Z-A ou 9-0).

```sql
SELECT nome, salario
FROM funcionarios
ORDER BY salario DESC;
```

> Ordena os funcionários do maior para o menor salário.

---

#### ✅ A cláusula `ORDER BY` deve ser **a última** em uma instrução `SELECT`

Isso significa que ela deve vir **depois** de cláusulas como `WHERE`, `GROUP BY` e `HAVING`.

Exemplo com `WHERE`:

```sql
SELECT nome, salario
FROM funcionarios
WHERE departamento_id = 10
ORDER BY nome;
```

#### Utilizando Variáveis de Substituição - &

- Utilize uma variável prefixada com um (&) para solicitar um prompt para o usuário digitar um valor


---

### 📘 Explicação com Exemplo em Oracle SQL

As variáveis de substituição com `&` são utilizadas no Oracle SQL*Plus (ou ferramentas compatíveis como SQL Developer) para permitir entrada dinâmica de valores.

---

#### 🔹 Como funciona:

Quando você usa `&nome_variavel`, o Oracle solicita que o usuário digite um valor para substituir a variável no momento da execução.

---

#### ✅ Exemplo:

```sql
SELECT * 
FROM funcionarios 
WHERE departamento_id = &departamento;
```

> Ao executar este comando, será exibido um prompt:  
`Enter value for departamento:`  
Se o usuário digitar `10`, o comando executado será:

```sql
SELECT * 
FROM funcionarios 
WHERE departamento_id = 10;
```

---

#### 🔁 Exemplo com várias variáveis:

```sql
SELECT * 
FROM funcionarios 
WHERE salario BETWEEN &salario_min AND &salario_max;
```

> O usuário será solicitado a informar dois valores: `salario_min` e `salario_max`.

---

Essas variáveis são muito úteis para **criar scripts reutilizáveis** e **consultas parametrizadas** em ambientes de aprendizado e administração.

---

#### Utilizando Variáveis de Substituição - &&

Utilize `&&` se você deseja reutilizar o valor da variável sem solicitar um prompt para o usuário a cada vez que referenciar a variável:

```sql
SELECT employee_id, last_name, salary, department_id
FROM employees
WHERE employee_id = &&employee_id;
```

---

### 📘 Explicação sobre `&&` em Oracle SQL

No Oracle SQL (usando ferramentas como SQL*Plus ou Oracle SQL Developer), a variável `&&nome` permite reutilizar o valor digitado uma única vez **sem reexibir o prompt** toda vez que a variável for usada novamente.

---

#### ✅ Exemplo Prático:

```sql
SELECT employee_id, last_name
FROM employees
WHERE employee_id = &&id;
```

> O Oracle irá solicitar **uma única vez**:  
`Enter value for id:`  
Se o usuário digitar `101`, o valor `101` será armazenado na variável `id` e poderá ser reutilizado **em outros comandos subsequentes**, sem solicitar novamente.

---

#### 🔁 Exemplo com Reutilização:

```sql
SELECT * FROM employees WHERE employee_id = &&id;
SELECT * FROM job_history WHERE employee_id = &&id;
```

> Ambos os comandos usarão o mesmo valor digitado para `id`.

---

Isso é especialmente útil para scripts em que o mesmo parâmetro será usado em várias partes, mantendo a entrada do usuário enxuta e eficiente.

```
-- Variáveis de substituição com valores tipo Character e Date

SELECT last_name, department_id, job_id, salary*12
FROM employees
WHERE job_id = '&job_id' ;

```

```
-- Utilizando o comando DEFINE

DEFINE employee_id = 101

SELECT employee_id, last_name, salary, department_id
FROM employees
WHERE employee_id = &employee_id ;

DEFINE employee_id

UNDEFINE employee_id
```


[Voltar ao Índice](#indice)

---


## <a name="parte8">8 - Seção 08: Oracle SQL - Utilizando Funções Single Row</a>

- 15. Oracle SQL - Utilizando Funções Single Row

- [recursos/Seção+8+-+Prática+Aula+1.sql](/recursos/Seção+8+-+Prática+Aula+1.sql)

### Resumo dos Slides da Aula

![img/15_1_func_singleRow.png](/img/15_1_func_singleRow.png)

![img/15_2_tipos_func.png](/img/15_2_tipos_func.png)

#### Funções SQL Single Row

#### Características:
- Podem manipular itens de dados  
- Receber argumentos e retornar um valor  
- Atuam sobre cada linha retornada  
- Retornam um resultado por linha  
- Podem modificar o tipo de dado  
- Podem ser aninhadas  
- Recebem argumentos que podem ser colunas ou expressões  

![alt text](img/15_3_tipos_func.png)

![alt text](/img/15_4_tipos_character.png)

![alt text](/img/15_5_func-maiu_minu.png)

```sql
-- Funções de conversão Maiúsculo & Minúsculo

SELECT employee_id, last_name, department_id
FROM employees
WHERE last_name = 'KING';

SELECT employee_id, last_name, department_id
FROM employees
WHERE UPPER(last_name) = 'KING';
```

![alt text](/img/15_6_func_man_carac.png)

```sql
-- Funções de Manipulação de Caracteres

SELECT CONCAT(' Curso: ','Introdução ORACLE 19c'), SUBSTR('Introdução ORACLE 19c',1,11),
       LENGTH('Introdução ORACLE 19c'), INSTR('Introdução ORACLE 19c','ORACLE')
FROM dual;
```

![alt text](/img/15_7_func_caracter.png)

```sql
SELECT first_name "Nome", LPAD(first_name, 20, ' ') "Nome alinhado a direita", RPAD(first_name, 20, ' ') "Nome alinhado a esquerda"
FROM   employees;

SELECT job_title, REPLACE(job_title, 'President', 'Presidente') CARGO
FROM jobs
WHERE  job_title = 'President';
```

#### Funções tipo NUMBER

- **ROUND**: Arredonda o valor para a casa decimal especificada  
- **TRUNC**: Trunca o valor para a casa decimal especificada  
- **MOD**: Retorna o resto da divisão  

```sql
SELECT ROUND(45.923,2), ROUND(45.923,0)
FROM dual;


ROUND(45.923,2) ROUND(45.923,0)
--------------- ---------------
          45.92              46


SELECT TRUNC(45.923,2), TRUNC(45.923,0)
FROM dual;


TRUNC(45.923,2) TRUNC(45.923,0)
--------------- ---------------
          45.92              45


SELECT MOD(1300,600) RESTO
FROM dual;


     RESTO
----------
       100

```

![alt text](/img/15_8_funcTipoNumber.png)

```sql
SELECT ABS(-9), SQRT(9)
FROM dual;


   ABS(-9)    SQRT(9)
---------- ----------
         9          3

```

#### Funções tipo DATE - Trabalhando com Datas

- O format default de exibição de datas é definido pelo DBA através do parâmetro NLS_DATE_FORMAT  
- No Brasil normalmente o formato default de exibição de datas é definido para ‘DD/MM/YY’ ou ‘DD/MM/RR’

```sql
-- Funções tipo DATE 

SELECT sysdate
FROM dual;

DESC dual

SELECT *
FROM dual;

SELECT 30000 * 1.25
FROM dual;

```

#### Cálculos com Datas

- Uma vez que o banco de dados armazena datas como números, você pode executar cálculos utilizando os operadores aritméticos como a adição e subtração.

![alt text](/img/15_9_calculaDatas.png)

```sql
SELECT sysdate, sysdate + 30, sysdate + 60, sysdate - 30
FROM dual;

SYSDATE   SYSDATE+3 SYSDATE+6 SYSDATE-3
--------- --------- --------- ---------
03-MAY-25 02-JUN-25 02-JUL-25 03-APR-25


SELECT last_name, ROUND((SYSDATE-hire_date)/7,2) "SEMANAS DE TRABALHO'"
FROM employees;

LAST_NAME                 SEMANAS DE TRABALHO'
------------------------- --------------------
OConnell                                932.34
Grant                                   902.91
Whalen                                 1128.48
Hartstein                              1106.63
Fay                                    1028.48
Mavris                                  1195.2
Baer                                    1195.2
Higgins                                 1195.2
Gietz                                   1195.2
King                                   1141.63
Kochhar                                1023.48

```

#### Outras Funções tipo DATE

| **Função**         | **Resultado**                          |
|--------------------|----------------------------------------|
| MONTHS_BETWEEN     | Número de meses entre duas datas       |
| ADD_MONTHS         | Adiciona meses a uma data              |
| NEXT_DAY           | Próximo dia relativo a data especificada |
| LAST_DAY           | Último dia do mês                      |
| ROUND              | Arredonda a data                       |
| TRUNC              | Trunca a data                          |

```sql
SELECT first_name, last_name, ROUND(MONTHS_BETWEEN(sysdate, hire_date),2) "MESES DE TRABALHO"
FROM employees;

--ERRO
SELECT SYSDATE, ADD_MONTHS(SYSDATE, 3), NEXT_DAY(SYSDATE,'SEXTA FEIRA'), LAST_DAY(SYSDATE)
FROM   dual;

SELECT SYSDATE, ADD_MONTHS(SYSDATE, 3), NEXT_DAY(SYSDATE,'FRIDAY'), LAST_DAY(SYSDATE)
FROM dual;

ALTER SESSION SET NLS_LANGUAGE = 'PORTUGUESE';
SELECT SYSDATE, ADD_MONTHS(SYSDATE, 3), NEXT_DAY(SYSDATE,'SEXTA-FEIRA'), LAST_DAY(SYSDATE)
FROM dual;
```

![alt text](/img/15_10_funcDate.png)


```sql

SELECT sysdate, ROUND(SYSDATE, 'MONTH'), ROUND(SYSDATE, 'YEAR'), 
       TRUNC(SYSDATE, 'MONTH'), TRUNC(SYSDATE, 'YEAR')
FROM   dual;
       
SELECT SYSDATE, TO_CHAR(TRUNC(SYSDATE),'DD/MM/YYYY HH24:MI:SS')
FROM  dual;


```




### Resumo AI- DEEPSEEAK

# Resumo: Oracle SQL - Funções Single Row

## Visão Geral
Funções Single Row (ou funções de linha única) operam em uma única linha por vez e retornam um resultado para cada linha processada. Elas são usadas para manipular dados, realizar cálculos e formatar resultados.

---

## Tipos e Exemplos de Funções Single Row

### 1. Funções de Caractere
- **UPPER()**: Converte para maiúsculas
  ```sql
  SELECT UPPER(nome) FROM clientes;
  ```
- **LOWER()**: Converte para minúsculas
  ```sql
  SELECT LOWER(descricao) FROM produtos;
  ```
- **INITCAP()**: Primeira letra maiúscula
  ```sql
  SELECT INITCAP('oracle database') FROM dual; -- Retorna "Oracle Database"
  ```

### 2. Funções Numéricas
- **ROUND()**: Arredondamento
  ```sql
  SELECT ROUND(123.456, 2) FROM dual; -- Retorna 123.46
  ```
- **TRUNC()**: Truncamento
  ```sql
  SELECT TRUNC(123.456, 1) FROM dual; -- Retorna 123.4
  ```
- **MOD()**: Módulo (resto da divisão)
  ```sql
  SELECT MOD(10, 3) FROM dual; -- Retorna 1
  ```

### 3. Funções de Data
- **SYSDATE**: Data/hora atual
  ```sql
  SELECT SYSDATE FROM dual;
  ```
- **TO_CHAR()**: Formatação de data
  ```sql
  SELECT TO_CHAR(SYSDATE, 'DD/MM/YYYY HH24:MI') FROM dual;
  ```
- **MONTHS_BETWEEN()**: Diferença em meses
  ```sql
  SELECT MONTHS_BETWEEN('01-JAN-2025', '01-MAR-2024') FROM dual;
  ```

### 4. Funções de Conversão
- **TO_NUMBER()**: Converte para número
  ```sql
  SELECT TO_NUMBER('1234') FROM dual;
  ```
- **TO_DATE()**: Converte para data
  ```sql
  SELECT TO_DATE('10/05/2025', 'DD/MM/YYYY') FROM dual;
  ```

### 5. Funções Condicionais
- **NVL()**: Substitui valores nulos
  ```sql
  SELECT NVL(comissao, 0) FROM vendedores;
  ```
- **DECODE()**: Condicional simples
  ```sql
  SELECT DECODE(status, 'A', 'Ativo', 'I', 'Inativo', 'Desconhecido') FROM usuarios;
  ```

---

## Melhores Práticas

1. **Use aliases para melhor legibilidade**
   ```sql
   SELECT UPPER(nome) AS nome_maiusculo FROM clientes;
   ```

2. **Evite funções em colunas indexadas em WHERE** (pode impedir uso de índices)
   ```sql
   -- RUIM (não usa índice na coluna nome)
   SELECT * FROM clientes WHERE UPPER(nome) = 'JOÃO';
   
   -- MELHOR (considerar armazenar já em maiúsculas ou usar índice function-based)
   ```

3. **Documente conversões complexas**
   ```sql
   -- Formata CPF (documentar o padrão)
   SELECT REGEXP_REPLACE(cpf, '(\d{3})(\d{3})(\d{3})(\d{2})', '\1.\2.\3-\4') AS cpf_formatado
   FROM clientes;
   ```

4. **Trate NULLs explicitamente**
   ```sql
   SELECT NVL(telefone, 'Sem telefone') AS contato FROM clientes;
   ```

---

## Piores Práticas (Evitar)

1. **Aninhamento excessivo de funções**
   ```sql
   -- Difícil de ler e manter
   SELECT TO_CHAR(LAST_DAY(ADD_MONTHS(SYSDATE, 3)), 'DD-MM-YYYY') FROM dual;
   ```

2. **Ignorar localidade em conversões**
   ```sql
   -- Pode falhar em ambientes com configuração diferente
   SELECT TO_DATE('01/02/2025', 'MM/DD/YYYY') FROM dual;
   ```

3. **Usar funções em JOINs sem necessidade**
   ```sql
   -- Performance ruim
   SELECT * FROM tabela1 t1
   JOIN tabela2 t2 ON UPPER(t1.chave) = UPPER(t2.chave);
   ```

4. **Não tratar erros em conversões**
   ```sql
   -- Pode causar erro se houver valores não numéricos
   SELECT TO_NUMBER(codigo) FROM produtos;
   
   -- MELHOR: Usar tratamento de erro ou VALIDATE_CONVERSION no Oracle 12c+
   ```

---

## Exemplo Complexo Combinado

```sql
-- Formata endereço completo com tratamento de nulos
SELECT 
    id_cliente,
    INITCAP(nome) || ' - ' ||
    NVL2(complemento, 
         RTRIM(endereco) || ', ' || INITCAP(complemento), 
         RTRIM(endereco)) || ', ' ||
    INITCAP(cidade) || '/' || UPPER(uf) AS endereco_completo,
    TO_CHAR(data_cadastro, 'DD "de" Month YYYY', 'NLS_DATE_LANGUAGE=PORTUGUESE') AS data_cadastro_br
FROM clientes
WHERE MONTHS_BETWEEN(SYSDATE, data_nascimento)/12 > 18;
```

---

## Conclusão
Funções Single Row são poderosas, mas devem ser usadas com cuidado para:
- Manter a legibilidade do código
- Não comprometer a performance
- Garantir consistência dos resultados



[Voltar ao Índice](#indice)

---


## <a name="parte9">9 - Seção 09: Oracle SQL - Utilizando Funções de Conversão e Expressões Condicionais</a>

- 16 Oracle SQL - Utilizando Funções de Conversão e Expressões Condicionais

[recursos/Seção+9+-+Prática+Aula+1.sql](recursos/Seção+9+-+Prática+Aula+1.sql)


#### RESUMO SLIDES AULA

![alt text](img/16_1_tiposConversao.png)

![alt text](img/16_2_tipoDadosDePara.png)

![alt text](img/16_3_conversaoExplicita.png)

#### Utilizando a Função TO_CHAR com Datas

**Sintaxe:**  
`TO_CHAR(date, 'formato')`  

**Regras do formato:**  
- Deve ser definido entre aspas simples  
- É case-sensitive (sensível a maiúsculas/minúsculas)  
- Pode incluir quaisquer formatos de datas válidos  
- O prefixo `fm` remove espaços em branco desnecessários ou zeros à esquerda  
- Deve ser separado do valor da data por vírgula  

**Exemplo Prático Oracle:**  
```sql
SELECT 
    TO_CHAR(SYSDATE, 'fmDD "de" Month YYYY', 'NLS_DATE_LANGUAGE=PORTUGUESE') AS data_formatada
FROM dual;
-- Resultado: "15 de Julho 2025" (sem zeros ou espaços extras)
```

```sql
-- Utilizando a Função TO_CHAR com Datas

SELECT last_name,TO_CHAR(hire_date, 'DD/MM/YYYY  HH24:MI:SS') DT_ADMISSÂO
FROM employees;


LAST_NAME                 DT_ADMISSÂO         
------------------------- --------------------
OConnell                  21/06/2007  00:00:00
Grant                     13/01/2008  00:00:00
Whalen                    17/09/2003  00:00:00
Hartstein                 17/02/2004  00:00:00
Fay                       17/08/2005  00:00:00
Mavris                    07/06/2002  00:00:00
Baer                      07/06/2002  00:00:00
Higgins                   07/06/2002  00:00:00


SELECT sysdate,TO_CHAR(sysdate, 'DD/MM/YYYY  HH24:MI:SS') DATA
FROM   dual;

YSDATE   DATA                
--------- --------------------
03-MAY-25 03/05/2025  16:00:04


SELECT last_name, TO_CHAR(hire_date, 'DD, "de" Month "de" YYYY') DT_ADMISSÂO
FROM employees;


LAST_NAME                 DT_ADMISSÂO                                        
------------------------- ---------------------------------------------------
OConnell                  21, de June      de 2007                           
Grant                     13, de January   de 2008                           
Whalen                    17, de September de 2003                           
Hartstein                 17, de February  de 2004                           
Fay                       17, de August    de 2005   


SELECT last_name, TO_CHAR(hire_date, 'FMDD, "de" Month "de" YYYY') DT_ADMISSÂO
FROM employees;


LAST_NAME                 DT_ADMISSÂO                                        
------------------------- ---------------------------------------------------
OConnell                  21, de June de 2007                                
Grant                     13, de January de 2008                             
Whalen                    17, de September de 2003                           
Hartstein                 17, de February de 2004                            
Fay                       17, de August de 2005                              
Mavris                    7, de June de 2002                                 
Baer                      7, de June de 2002        

```

![alt text](img//16_4_To_CHAR.png)

```sql
-- Utilizando a Função TO_CHAR com Números

SELECT first_name, last_name, TO_CHAR(salary, 'L99G999G999D99') SALARIO
FROM employees;


FIRST_NAME           LAST_NAME                 SALARIO                 
-------------------- ------------------------- ------------------------
Donald               OConnell                                 $2,600.00
Douglas              Grant                                    $2,600.00
Jennifer             Whalen                                   $4,400.00
Michael              Hartstein                               $13,000.00
Pat                  Fay                                      $6,000.00

SELECT first_name, last_name, TO_CHAR(salary, 'L99G999G999D99') SALARIO
FROM employees;


FIRST_NAME           LAST_NAME                 SALARIO                 
-------------------- ------------------------- ------------------------
Donald               OConnell                                 $2,600.00
Douglas              Grant                                    $2,600.00
Jennifer             Whalen                                   $4,400.00
Michael              Hartstein                               $13,000.00
Pat                  Fay                                      $6,000.00
```

#### Utilizando a Função TO_NUMBER

**Função de Conversão:**  
`TO_NUMBER(char[, 'formato'])`  

**Propósito:**  
Converter uma string de caracteres para um valor numérico.

**Características:**  
- O parâmetro `char` representa a string a ser convertida  
- O parâmetro opcional `'formato'` especifica o padrão de formatação numérica  
- Requer que a string contenha apenas caracteres numéricos válidos  

**Exemplo Prático Oracle:**  
```sql
SELECT TO_NUMBER('1.234,56', '9G999D99') AS valor_numérico
FROM dual;
-- Converte a string "1.234,56" para o número 1234.56
```


#### Utilizando a Função TO_DATE

**Função de Conversão:**  
`TO_DATE(char[, 'formato'])`  

**Propósito:**  
Converter uma string de caracteres para um valor do tipo DATE.

**Características:**  
- `char`: String contendo a data a ser convertida  
- `'formato'` (opcional): Especifica o padrão da data na string  
- Se omitido, usa o formato padrão NLS_DATE_FORMAT  

**Exemplos Oracle:**  
```sql
-- Conversão básica
SELECT TO_DATE('15/07/2025', 'DD/MM/YYYY') FROM dual;

-- Com formato completo
SELECT TO_DATE('15-Jul-2025 14:30', 'DD-Mon-YYYY HH24:MI') FROM dual;

-- Usando máscara FM para remover espaços extras
SELECT TO_DATE('15   Jul    2025', 'fmDD Mon YYYY') FROM dual;
```

**Melhores Práticas:**  
1. **Sempre especifique o formato** para evitar ambiguidades  
2. **Use prefixo FM** para strings com espaços inconsistentes  
3. **Considere NLS_DATE_LANGUAGE** para meses em outros idiomas:  

```sql
ALTER SESSION SET NLS_DATE_LANGUAGE = 'PORTUGUESE';
SELECT TO_DATE('15-Julho-2025', 'DD-Month-YYYY') FROM dual;
```

#### Funções Aninhadas

**Princípio Básico:**
- Funções single-row podem ser aninhadas em múltiplos níveis
- A avaliação ocorre de dentro para fora (do nível mais profundo para o mais externo)

**Sintaxe Genérica:**
```sql
F3(F2(F1(col, arg1), arg2), arg3)
```

**Exemplo Prático Oracle:**
```sql
-- Exemplo com 3 níveis de aninhamento
SELECT 
    UPPER(TO_CHAR(LAST_DAY(ADD_MONTHS(SYSDATE, 3)), 'DD-MON-YYYY')) AS data_processamento
FROM dual;
/* Fluxo de execução:
1. ADD_MONTHS(SYSDATE, 3) → Adiciona 3 meses à data atual
2. LAST_DAY() → Pega o último dia do mês resultante
3. TO_CHAR() → Formata como string
4. UPPER() → Converte para maiúsculas
*/
```

**Regras Importantes:**
1. **Ordem de Execução:** O Oracle sempre resolve primeiro a função mais interna
2. **Limite de Níveis:** Suporta até ~200 níveis de aninhamento (praticamente ilimitado)
3. **Legibilidade:** Recomenda-se no máximo 5-7 níveis para manter o código compreensível

**Boas Práticas:**
```sql
-- Formato recomendado para aninhamentos complexos
SELECT
    RPAD(
        SUBSTR(
            INITCAP(nome_cliente),
            1,
            10
        ),
        15,
        '.'
    ) AS nome_formatado
FROM clientes;
```

**Aviso:** Evite aninhamentos excessivos que prejudiquem a legibilidade e performance.

#### Funções Genéricas

**Visão Geral:**  
Funções que operam com qualquer tipo de dado no Oracle Database.

**Principais Funções:**

| Função       | Sintaxe                     | Comportamento                                                                 |
|--------------|-----------------------------|-------------------------------------------------------------------------------|
| **NVL**      | `NVL(expr1, expr2)`         | Retorna `expr2` se `expr1` for NULL, caso contrário retorna `expr1`           |
| **NVL2**     | `NVL2(expr1, expr2, expr3)` | Retorna `expr2` se `expr1` não for NULL, ou `expr3` se `expr1` for NULL       |
| **NULLIF**   | `NULLIF(expr1, expr2)`      | Retorna NULL se `expr1` = `expr2`, caso contrário retorna `expr1`             |
| **COALESCE** | `COALESCE(expr1, ..., exprn)`| Retorna o primeiro valor não-NULL na lista de expressões                      |

**Exemplos Práticos:**

```sql
-- NVL: Substituição simples de NULL
SELECT nome, NVL(comissao, 0) AS comissao_ajustada FROM vendedores;

-- NVL2: Lógica condicional com NULL
SELECT produto, NVL2(estoque, 'Disponível', 'Esgotado') AS status FROM produtos;

-- NULLIF: Comparação para retornar NULL
SELECT NULLIF(salario_atual, salario_anterior) AS diferenca FROM empregados;

-- COALESCE: Primeiro valor não-nulo
SELECT COALESCE(telefone, celular, email, 'Sem contato') AS contato FROM clientes;
```

**Características Comuns:**
- Operam com qualquer tipo de dados (NUMBER, VARCHAR2, DATE, etc.)
- Todas tratam valores NULL de forma específica
- Podem ser aninhadas com outras funções
- Essenciais para tratamento de dados incompletos

**Melhor Prática:**  
Use `COALESCE` em vez de múltiplos `NVL` aninhados para maior clareza:

```sql
-- Em vez de:
SELECT NVL(col1, NVL(col2, NVL(col3, 'padrão'))) FROM tabela;

-- Prefira:
SELECT COALESCE(col1, col2, col3, 'padrão') FROM tabela;
```

#### Utilizando a Função COALESCE

**Comportamento:**
- Aceita múltiplos argumentos (2 ou mais expressões)
- Retorna o **primeiro valor não-NULL** na lista de expressões
- Se todas as expressões forem NULL, retorna NULL

**Fluxo de Avaliação:**
1. Avalia a primeira expressão:
   - Se **não for NULL**, retorna este valor (interrompe a avaliação)
   - Se for NULL, passa para a próxima expressão
2. Repete o processo até encontrar um valor não-NULL ou esgotar os argumentos

**Exemplo Prático Oracle:**
```sql
-- Retorna o primeiro valor não-nulo encontrado:
SELECT 
    COALESCE(telefone_residencial, 
             telefone_celular, 
             telefone_comercial, 
             'Nenhum contato disponível') AS contato_prioritario
FROM clientes;
```

**Caso Especial:**
```sql
-- Se todos forem NULL, retorna NULL (a menos que haja um valor padrão final)
SELECT COALESCE(NULL, NULL, NULL) FROM dual;  -- Retorna NULL
```

**Vantagens:**
- Mais elegante que múltiplos NVL aninhados
- Avaliação curto-circuito (otimizada)
- Pode ser usada com qualquer tipo de dado

**Comparação NVL vs COALESCE:**
```sql
-- Equivalência funcional:
SELECT NVL(col1, NVL(col2, 'padrão')) FROM tabela;  -- Com NVL aninhado
SELECT COALESCE(col1, col2, 'padrão') FROM tabela;   -- Mais limpo com COALESCE
```

#### Utilizando a Função NVL2

**Sintaxe:**  
```sql
  NVL2(expressão_avaliada, valor_se_nao_null, valor_se_null)
```

**Funcionamento:**  
- Avalia a `expressão_avaliada`:
  - Se **NÃO for NULL**, retorna `valor_se_nao_null`
  - Se **for NULL**, retorna `valor_se_null`

**Exemplo da Imagem:**
```sql
SELECT 
    last_name, 
    salary, 
    commission_pct,
    NVL2(commission_pct, 10, 0) AS PERCENTUAL_ATERADO
FROM employees;
```

**Resultado Esperado:**
- Para funcionários COM comissão (`commission_pct` ≠ NULL): retorna `10`
- Para funcionários SEM comissão (`commission_pct` = NULL): retorna `0`

**Exemplo Adicional:**
```sql
-- Aplicando aumento condicional
SELECT 
    product_name,
    price,
    NVL2(discount, price * 0.9, price) AS preco_final
FROM products;
```

**Vantagens:**
- Mais conciso que `CASE WHEN expressão IS NOT NULL THEN ... ELSE ... END`
- Funciona com qualquer tipo de dado no Oracle
- Avaliação de único passe (melhor performance)

#### Utilizando a Função NULLIF

**Sintaxe:**  
```sql
NULLIF(expressão1, expressão2)
```

**Comportamento:**  
- Compara os dois argumentos:
  - Se **forem iguais**, retorna `NULL`
  - Se **diferentes**, retorna o valor da primeira expressão (`expressão1`)

**Exemplo da Imagem:**
```sql
SELECT 
    NULLIF(1000, 1000),  -- Retorna NULL (valores iguais)
    NULLIF(1000, 2000)   -- Retorna 1000 (valores diferentes)
FROM dual;
```

**Saída Esperada:**
```
NULL    1000
```

**Casos de Uso Comuns:**
1. **Evitar divisão por zero:**
```sql
SELECT valor / NULLIF(total, 0) AS porcentagem FROM métricas;
```

2. **Identificar mudanças:**
```sql
SELECT 
    produto_id,
    NULLIF(preço_atual, preço_anterior) AS alteração_preço
FROM produtos;
```

**Regras Importantes:**
- Ambos os argumentos devem ser do mesmo tipo de dado
- Frequentemente usada com funções de agregação
- Alternativa mais elegante que `CASE WHEN expr1 = expr2 THEN NULL ELSE expr1 END`

**Exemplo Avançado:**
```sql
SELECT 
    cliente_id,
    NULLIF(TO_CHAR(última_compra, 'YYYY-MM'), 
          TO_CHAR(SYSDATE, 'YYYY-MM')) AS meses_com_compra
FROM clientes;
```

#### Expressões Condicionais

**Função:**  
Permitem implementar lógica condicional (IF-THEN-ELSE) diretamente em consultas SQL.

**Métodos Disponíveis:**

1. **Expressão CASE** (Padrão ANSI SQL)
   
```sql
CASE 
    WHEN condição1 THEN resultado1
    WHEN condição2 THEN resultado2
    ...
    ELSE resultado_padrão
END
```

2. **Expressão DECODE** (Específico do Oracle)
```sql
DECODE(coluna, 
      valor1, resultado1,
      valor2, resultado2,
      ...,
      resultado_padrão)
```

**Exemplo Prático:**

```sql
-- Usando CASE
SELECT nome,
       CASE
           WHEN salario > 10000 THEN 'Alto'
           WHEN salario > 5000 THEN 'Médio'
           ELSE 'Baixo'
       END AS faixa_salarial
FROM empregados;

-- Usando DECODE
SELECT produto,
       DECODE(categoria,
              'E', 'Eletrônico',
              'V', 'Vestuário',
              'Outros') AS tipo_produto
FROM produtos;
```

**Principais Diferenças:**
| **CASE** | **DECODE** |
|----------|------------|
| Padrão ANSI | Exclusivo Oracle |
| Aceita condições complexas | Comparações diretas de igualdade |
| Mais legível para múltiplas condições | Mais compacto para comparações simples |

**Melhor Prática:**  
Prefira `CASE` para condições complexas e `DECODE` para comparações simples de igualdade.






#### RESUMO GERAL COM AI - DEEPSEEK


### Visão Geral
Funções de conversão transformam dados entre tipos (texto, número, data), enquanto expressões condicionais permitem lógica condicional diretamente no SQL.

---

## 1. Funções de Conversão (Principais)

### TO_CHAR()
Converte números/datas para texto com formatação:

```sql
-- Data para texto
SELECT TO_CHAR(SYSDATE, 'DD/MM/YYYY HH24:MI:SS') FROM dual;

-- Número para texto formatado
SELECT TO_CHAR(1234.56, 'L999G999D99') FROM dual; -- Ex: "R$1.234,56"
```

### TO_NUMBER()
Converte texto para número:

```sql
SELECT TO_NUMBER('1.234,56', '9G999D99') FROM dual;
```

### TO_DATE()
Converte texto para data:

```sql
SELECT TO_DATE('15/03/2025', 'DD/MM/YYYY') FROM dual;
```

---

## 2. Expressões Condicionais

### CASE (Padrão ANSI)
```sql
SELECT nome,
       CASE 
          WHEN salario > 10000 THEN 'Alto'
          WHEN salario > 5000 THEN 'Médio'
          ELSE 'Baixo'
       END AS categoria_salario
FROM empregados;
```

### DECODE (Específico Oracle)
```sql
SELECT nome,
       DECODE(uf, 
              'SP', 'Paulista',
              'RJ', 'Carioca',
              'Outro') AS naturalidade
FROM clientes;
```

---

## Exemplos Complexos

### Combinação de Funções
```sql
SELECT TO_CHAR(
         ADD_MONTHS(
           TO_DATE('15/' || mes || '/' || ano, 'DD/MM/YYYY'),
           6
         ), 'Month YYYY'
       ) AS data_projetada
FROM tabela_temporal;
```

### Expressão Condicional com Agregação
```sql
SELECT departamento,
       COUNT(*) AS total,
       SUM(CASE WHEN salario > 5000 THEN 1 ELSE 0 END) AS acima_media
FROM empregados
GROUP BY departamento;
```

---

## Melhores Práticas ✅

1. **Sempre especifique formato em conversões**:
   ```sql
   -- Bom
   SELECT TO_DATE('15-03-2025', 'DD-MM-YYYY') FROM dual;
   ```

2. **Use CASE para lógica complexa** (mais legível que DECODE):
   ```sql
   CASE WHEN status = 'A' AND salario > 1000 THEN ... END
   ```

3. **Trate valores nulos explicitamente**:
   ```sql
   SELECT NVL(TO_CHAR(comissao, '999D99'), '0,00') FROM vendedores;
   ```

---

## Piores Práticas ❌ (Evitar)

1. **Conversão implícita** (pode causar erros):
   ```sql
   -- Ruim (depende da configuração do banco)
   SELECT * FROM pedidos WHERE data = '15/03/2025';
   ```

2. **Aninhamento excessivo de DECODE**:
   ```sql
   -- Difícil manutenção
   DECODE(col1, 'A', DECODE(col2, 'X', 1, 0), 0)
   ```

3. **Ignorar localidade em formatos**:
   ```sql
   -- Pode falhar em outros ambientes
   SELECT TO_NUMBER('1.234,56') FROM dual;
   ```

4. **Usar conversões em colunas indexadas**:
   ```sql
   -- Evite (invalida índices)
   SELECT * FROM clientes WHERE TO_CHAR(data_cadastro, 'YYYY') = '2025';
   ```

---

## Exemplo Completo (Boas Práticas)

```sql
-- Relatório formatado com tratamento de nulos e localização
SELECT 
    nome,
    TO_CHAR(data_nascimento, 'DD "de" Month YYYY', 
           'NLS_DATE_LANGUAGE=PORTUGUESE') AS nascimento_br,
    CASE
        WHEN meses_servico > 120 THEN 'Sênior'
        WHEN meses_servico > 60 THEN 'Pleno'
        ELSE 'Júnior'
    END AS senioridade,
    NVL(TO_CHAR(comissao, 'L999G990D00', 'NLS_NUMERIC_CHARACTERS='',.'''), 
        'Sem comissão') AS comissao_formatada
FROM vendedores
WHERE TO_DATE(data_contrato, 'DD/MM/YYYY') > ADD_MONTHS(SYSDATE, -24);
```

---

## Conclusão
- Funções de conversão garantem integridade dos tipos de dados
- Expressões condicionais trazem lógica para consultas SQL
- Sempre prefira formatação explícita e tratamento de erros
- Documente conversões complexas para manutenção futura


[Voltar ao Índice](#indice)

---


## <a name="parte10">10 - Seção 10: Oracle SQL - Agregando dados utilizando Funções de Grupo</a>

### 17 Oracle SQL - Agregando dados utilizando Funções de Grupo

- [Seção+10+-+Prática+Aula+1.sql](/recursos/Seção+10+-+Prática+Aula+1.sql)

#### Principais Funções de Grupo

- **AVG** - Calcula a média de valores  
- **COUNT** - Conta o número de linhas ou valores não nulos  
- **MAX** - Retorna o valor máximo  
- **MIN** - Retorna o valor mínimo  
- **SUM** - Soma todos os valores  
- **STDDEV** - Calcula o desvio padrão  
- **VARIANCE** - Calcula a variância estatística  

**Exemplo Básico Oracle:**
```sql
SELECT 
    AVG(salario) AS media_salarial,
    COUNT(*) AS total_funcionarios,
    MAX(data_admissao) AS ultima_admissao,
    MIN(salario) AS menor_salario,
    SUM(vendas) AS total_vendas,
    STDDEV(comissao) AS desvio_comissao,
    VARIANCE(notas) AS variancia_avaliacoes
FROM empregados;
```

**Observações:**
1. Todas as funções ignoram valores NULL (exceto COUNT(*))
2. Podem ser combinadas com GROUP BY para análise por grupos
3. STDDEV e VARIANCE são particularmente úteis para análise estatística

#### Utilizando as Funções AVG e SUM

**Características:**
- Operam exclusivamente com dados numéricos
- Ignoram valores NULL nos cálculos
- Podem ser usadas com cláusulas GROUP BY para análise segmentada

**Exemplos Oracle:**

```sql
-- Cálculo básico
SELECT 
    AVG(salario) AS média_salarial,
    SUM(vendas) AS total_vendas
FROM funcionarios;

-- Com filtros e agrupamento
SELECT 
    departamento,
    AVG(salario) AS média_dept,
    SUM(horas_extras) AS total_horas_extras
FROM empregados
WHERE data_contratacao > TO_DATE('01/01/2023', 'DD/MM/YYYY')
GROUP BY departamento;
```

**Diferenças Chave:**
| Função | Descrição | Comportamento com NULL |
|--------|-----------|------------------------|
| `AVG()` | Calcula média aritmética | Ignora valores NULL |
| `SUM()` | Soma valores | Ignora valores NULL |

**Melhor Prática:**
```sql
-- Use ROUND com AVG para controle de casas decimais
SELECT 
    departamento,
    ROUND(AVG(salario), 2) AS média_formatada
FROM empregados
GROUP BY departamento;
```

```sql
SELECT AVG(salary), SUM(salary) FROM   employees;

AVG(SALARY) SUM(SALARY)
----------- -----------
 6461.83178      691416
```

#### Utilizando as Funções MIN e MAX

**Características:**
- Operam com diversos tipos de dados:
  - Numéricos
  - Caracteres (texto)
  - Datas
- Ignoram valores NULL nos cálculos

**Exemplos Oracle:**

```sql
-- Com números
SELECT 
    MIN(preco) AS menor_preco,
    MAX(estoque) AS maior_estoque
FROM produtos;

-- Com texto (ordem alfabética)
SELECT 
    MIN(nome) AS primeiro_alfabetico,
    MAX(nome) AS ultimo_alfabetico
FROM clientes;

-- Com datas
SELECT 
    MIN(data_admissao) AS primeira_admissao,
    MAX(data_nascimento) AS mais_novo
FROM empregados;
```

**Comportamento por Tipo de Dado:**
| Tipo      | MIN Retorna | MAX Retorna |
|-----------|-------------|-------------|
| Numérico  | Menor valor | Maior valor |
| Texto     | Primeiro na ordem alfabética | Último na ordem alfabética |
| Data      | Data mais antiga | Data mais recente |

**Melhor Prática:**
```sql
-- Combine com TO_CHAR para formatar datas
SELECT 
    TO_CHAR(MIN(data_venda), 'DD/MM/YYYY') AS primeira_venda,
    TO_CHAR(MAX(data_venda), 'DD/MM/YYYY') AS ultima_venda
FROM vendas;
```

```sql
-- Utilizando as Funções MIN e MAX

SELECT MIN(hire_date), MAX(hire_date)
FROM   employees;

MIN(HIRE_ MAX(HIRE_
--------- ---------
13-JAN-01 21-APR-08


SELECT MIN(salary), MAX(salary)
FROM   employees;

MIN(SALARY) MAX(SALARY)
----------- -----------
       2100       24000
```

#### Utilizando a Função COUNT

**Comportamento:**
- `COUNT(*)` retorna o número total de linhas na tabela ou grupo (inclui NULLs e duplicatas)

**Exemplos Oracle:**

```sql
-- Contagem total de registros
SELECT COUNT(*) AS total_clientes FROM clientes;

-- Com filtro WHERE
SELECT COUNT(*) FROM pedidos WHERE status = 'FATURADO';

-- Com GROUP BY
SELECT departamento, COUNT(*) AS qtd_funcionarios
FROM empregados
GROUP BY departamento;
```

**Variações Importantes:**
1. `COUNT(*)` - Conta todas as linhas
2. `COUNT(coluna)` - Conta apenas valores não-NULL na coluna especificada
3. `COUNT(DISTINCT coluna)` - Conta valores únicos não-NULL

**Exemplo Prático:**
```sql
SELECT 
    COUNT(*) AS total_registros,
    COUNT(telefone) AS com_telefone,
    COUNT(DISTINCT cidade) AS cidades_unicas
FROM clientes;
```

**Melhor Prática:**
- Use `COUNT(1)` como alternativa mais eficiente a `COUNT(*)` em algumas versões do Oracle
- Para contagem de valores distintos, sempre use `COUNT(DISTINCT coluna)`



```sql
-- Utilizando a Função COUNT

SELECT COUNT(*)
FROM   employees;

  COUNT(*)
----------
       107

SELECT COUNT(commission_pct)
FROM   employees;

COUNT(COMMISSION_PCT)
---------------------
                   35

SELECT COUNT(commission_pct), COUNT(*)
FROM employees;


COUNT(COMMISSION_PCT)   COUNT(*)
--------------------- ----------
                   35        107


SELECT COUNT(NVL(commission_pct,0))
FROM employees;

COUNT(NVL(COMMISSION_PCT,0))
----------------------------
                         107


-- Utilizando a Função COUNT com DISTINCT

SELECT COUNT(DISTINCT department_id)
FROM   employees;

COUNT(DISTINCTDEPARTMENT_ID)
----------------------------
                          11

SELECT COUNT(department_id)
FROM   employees;

COUNT(DEPARTMENT_ID)
--------------------
                 106
```

#### Funções de Grupo e valores NULOS

**Comportamento Fundamental:**
- Todas as funções de grupo **ignoram automaticamente** valores NULL em seus cálculos

**Exceção Notável:**
```sql
COUNT(*)  -- Conta TODAS as linhas, inclusive as com NULL
```

**Exemplos Oracle:**

```sql
-- AVG ignora NULLs no cálculo da média
SELECT AVG(comissao) FROM vendedores;  -- Soma apenas valores não-nulos

-- SUM não considera NULLs
SELECT SUM(bonus) FROM funcionarios;   -- NULLs são tratados como zero na soma

-- COUNT(coluna) exclui NULLs
SELECT COUNT(email) FROM clientes;     -- Conta apenas emails válidos
```

**Comparação de Comportamento:**

| Função   | Tratamento de NULL       | Exemplo Resultado |
|----------|--------------------------|-------------------|
| `AVG()`  | Ignorado                 | `(10+20)/2 = 15` (se um valor for NULL) |
| `COUNT(*)` | Inclui linhas com NULL  | Conta todas as linhas da tabela |
| `MAX()`  | Ignorado                 | Retorna o maior valor não-NULL |

**Melhor Prática:**

```sql
-- Use NVL para substituir NULLs quando necessário
SELECT AVG(NVL(comissao, 0)) FROM vendedores;  -- Trata NULL como zero
```

```sql
-- Funções de Grupo e valores NULOS

SELECT AVG(commission_pct)
FROM   employees;


AVG(COMMISSION_PCT)
-------------------
         .222857143

-- Tratamento de NULOS em Funções de Grupo 

SELECT AVG(NVL(commission_pct, 0))
FROM   employees;

AVG(NVL(COMMISSION_PCT,0))
--------------------------
               .0728971963
```

### 18 Oracle SQL - Criando e Selecionando Grupos

- [Seção+10+-+Prática+Aula+2.sql](/recursos/Seção+10+-+Prática+Aula+2.sql)


#### Criando Grupos utilizando a Cláusula GROUP BY

**Sintaxe Básica:**
```sql
SELECT coluna, função_grupo(coluna)  
FROM tabela  
[WHERE condição]  
[GROUP BY expressão_group_by]  
[ORDER BY coluna];
```

**Exemplo Prático Oracle:**
```sql
-- Agrupamento simples
SELECT 
    departamento, 
    AVG(salario) AS media_salarial
FROM empregados
GROUP BY departamento;

-- Com múltiplas colunas e filtro
SELECT 
    departamento,
    cargo,
    COUNT(*) AS quantidade
FROM empregados
WHERE data_contratacao > TO_DATE('01/01/2023', 'DD/MM/YYYY')
GROUP BY departamento, cargo
ORDER BY departamento;
```

**Regras Essenciais:**
1. Todas as colunas não-agregadas no SELECT devem estar no GROUP BY
2. A cláusula WHERE filtra linhas **antes** do agrupamento
3. Use ORDER BY para ordenar os resultados finais

**Cenário Complexo:**
```sql
-- Agrupamento com JOIN e função de data
SELECT 
    TO_CHAR(v.data_venda, 'YYYY-MM') AS mes_venda,
    p.categoria,
    SUM(v.valor) AS total_vendas,
    COUNT(DISTINCT v.cliente_id) AS clientes_ativos
FROM vendas v
JOIN produtos p ON v.produto_id = p.id
GROUP BY TO_CHAR(v.data_venda, 'YYYY-MM'), p.categoria
HAVING SUM(v.valor) > 10000
ORDER BY mes_venda;
```

**Boas Práticas:**
- Liste colunas do GROUP BY na mesma ordem do SELECT
- Use aliases para melhor legibilidade
- Para filtros pós-agrupação, use HAVING em vez de WHERE

#### Sequência Lógica

1. WHERE – Selecionar as linhas a serem recuperadas  
2. GROUP BY – Formar os grupos *  
3. HAVING – Selecionar os grupos a serem recuperados  
4. Exibir colunas ou expressões do SELECT ordenando pelo critério definido no ORDER BY  

#### Utilizando a Cláusula GROUP BY

- Se o comando SELECT utiliza Grupos, então todas as colunas ou expressões na lista da cláusula SELECT que não estão em uma Função de Grupo devem estar na cláusula GROUP BY

```sql

-- Utilizando a clásula Group by com mais de uma Coluna ou Expressão

SELECT department_id, job_id, SUM(salary)
FROM employees
GROUP BY department_id, job_id
ORDER BY department_id, job_id;

DEPARTMENT_ID JOB_ID     SUM(SALARY)
------------- ---------- -----------
           10 AD_ASST           4400
           20 MK_MAN           13000
           20 MK_REP            6000
           30 PU_CLERK         13900
           30 PU_MAN           11000

SELECT department_id, job_id, SUM(salary)
FROM employees
GROUP BY department_id, job_id
ORDER BY department_id, job_id;


DEPARTMENT_ID JOB_ID     SUM(SALARY)
------------- ---------- -----------
           10 AD_ASST           4400
           20 MK_MAN           13000
           20 MK_REP            6000
           30 PU_CLERK         13900
           30 PU_MAN           11000
           40 HR_REP            6500
```

#### Consultas incorretas utilizando Funções de Grupo

- Você não pode utilizar a cláusula WHERE para restringir grupos  
- Você não pode utilizar Funções de Grupo na cláusula WHERE  

Obs: Utilize a cláusula HAVING para restringir grupos

```sql
-- Corrigindo consultas incorretas utilizando Funções de Grupo

SELECT department_id,  AVG(salary)
FROM employees
GROUP BY department_id;

-- Consultas incorretas utilizando Funções de Grupo

SELECT department_id, MAX(salary)
FROM   employees
WHERE  MAX(salary) > 10000
GROUP BY department_id;

```

```sql
-- Corrigindo consultas incorretas utilizando Funções de Grupo

-- Restringindo Grupos utilizando a cláusula HAVING

SELECT department_id, MAX(salary)
FROM   employees
GROUP BY department_id
HAVING MAX(salary)>10000;

SELECT job_id, SUM(salary) TOTAL
FROM   employees
WHERE  job_id <> 'SA_REP'
GROUP BY job_id
HAVING   SUM(salary) > 10000
ORDER BY SUM(salary);
```

```sql

-- Aninhando Funções de Grupo

SELECT MAX(AVG(salary))
FROM employees
GROUP BY department_id;

SELECT AVG(salary)
FROM   employees
GROUP BY department_id;
```



[Voltar ao Índice](#indice)

---


## <a name="parte11">11 - Seção 11: Oracle SQL - Exibindo dados a partir de Múltiplas Tabelas</a>

### 19 Oracle SQL - Exibindo dados a partir de Múltiplas Tabelas

- [recursos/Seção+11+-+Prática+Aula+1.sql](/recursos/Seção+11+-+Prática+Aula+1.sql)

#### Tipos de Joins compatíveis com SQL ANSI 1999

- Natural joins:
  - NATURAL JOIN
  - USING
  - ON
- OUTER joins:
  - LEFT OUTER JOIN
  - RIGHT OUTER JOIN
  - FULL OUTER JOIN
- Cross join

#### Qualificando nomes de colunas ambíguos

- Utilize prefixos de tabela para qualificar nomes de colunas que são iguais em múltiplas tabelas  
- Utilize prefixos de tabela para otimizar a performance  

```sql

-- Utilizando Prefixos Coluna com Nomes de Tabela 

SELECT employees.employee_id, employees.last_name, 
       employees.department_id, departments.department_name
FROM   employees JOIN departments 
       ON (employees.department_id = departments.department_id);
```
| EMPLOYEE\_ID | LAST\_NAME | DEPARTMENT\_ID | DEPARTMENT\_NAME |
| :--- | :--- | :--- | :--- |
| 200 | Whalen | 10 | Administration |
| 201 | Hartstein | 20 | Marketing |
| 202 | Fay | 20 | Marketing |
| 114 | Raphaely | 30 | Purchasing |
| 119 | Colmenares | 30 | Purchasing |
| 115 | Khoo | 30 | Purchasing |
| 116 | Baida | 30 | Purchasing |
| 117 | Tobias | 30 | Purchasing |
| 118 | Himuro | 30 | Purchasing |
| 203 | Mavris | 40 | Human Resources |


#### Qualificando nomes de colunas ambíguos

- Ao invés de prefixos com o nome completo da tabela utilize Alias de Tabela  
- Alias de Tabela podem ser nomes abreviados mantendo o código SQL menor e utilizando menos memória  
- Utilize Alias de Tabela para diferenciar colunas que possuem nomes idênticos, mas residem em tabelas diferentes  

```sql
-- Utilizando Alias de Tabela

SELECT e.employee_id, e.last_name, e.department_id, d.department_name
FROM   employees e JOIN departments d
ON     (e.department_id = d.department_id);
```

| EMPLOYEE\_ID | LAST\_NAME | DEPARTMENT\_ID | DEPARTMENT\_NAME |
| :--- | :--- | :--- | :--- |
| 200 | Whalen | 10 | Administration |
| 201 | Hartstein | 20 | Marketing |
| 202 | Fay | 20 | Marketing |
| 114 | Raphaely | 30 | Purchasing |
| 119 | Colmenares | 30 | Purchasing |
| 115 | Khoo | 30 | Purchasing |
| 116 | Baida | 30 | Purchasing |
| 117 | Tobias | 30 | Purchasing |
| 118 | Himuro | 30 | Purchasing |
| 203 | Mavris | 40 | Human Resources |

#### Criando Natural Joins

- A cláusula NATURAL JOIN é baseada em todas as colunas nas duas tabelas que possuem e o mesmo nome  
- Seleciona as linhas a partir das duas tabelas que possuem valores iguais em todas colunas envolvidas na cláusula  
- Se as colunas possuem o mesmo nome, mas possuem diferentes tipos de dados, um erro será retornado  

```sql
-- Utilizando Natural Joins

SELECT  department_id, department_name, location_id, city
FROM    departments
NATURAL JOIN locations;
```
| DEPARTMENT\_ID | DEPARTMENT\_NAME | LOCATION\_ID | CITY |
| :--- | :--- | :--- | :--- |
| 60 | IT | 1400 | Southlake |
| 50 | Shipping | 1500 | South San Francisco |
| 10 | Administration | 1700 | Seattle |
| 30 | Purchasing | 1700 | Seattle |
| 90 | Executive | 1700 | Seattle |
| 100 | Finance | 1700 | Seattle |
| 110 | Accounting | 1700 | Seattle |
| 120 | Treasury | 1700 | Seattle |
| 130 | Corporate Tax | 1700 | Seattle |
| 140 | Control And Credit | 1700 | Seattle |

#### JOIN com a Cláusula USING – SQL ANSI 1999

SELECT tabela.coluna, tabela.coluna  
FROM tabela  
JOIN tabela USING (nome_coluna)

```sql
-- JOIN com a Cláusula USING

SELECT e.employee_id, e.last_name, d.location_id, department_id, d.department_name
FROM employees e
  JOIN departments d USING (department_id);
```
| EMPLOYEE\_ID | LAST\_NAME | LOCATION\_ID | DEPARTMENT\_ID | DEPARTMENT\_NAME |
| :--- | :--- | :--- | :--- | :--- |
| 200 | Whalen | 1700 | 10 | Administration |
| 201 | Hartstein | 1800 | 20 | Marketing |
| 202 | Fay | 1800 | 20 | Marketing |
| 114 | Raphaely | 1700 | 30 | Purchasing |
| 119 | Colmenares | 1700 | 30 | Purchasing |
| 115 | Khoo | 1700 | 30 | Purchasing |
| 116 | Baida | 1700 | 30 | Purchasing |
| 117 | Tobias | 1700 | 30 | Purchasing |
| 118 | Himuro | 1700 | 30 | Purchasing |
| 203 | Mavris | 2400 | 40 | Human Resources |


#### Utilizando Alias de Tabela com a Cláusula USING

- Não qualifique (prefixe) uma coluna que é utilizada na cláusula USING

```sql
-- Join com a Cláusula ON

SELECT e.employee_id, e.last_name, e.department_id, d.location_id
FROM employees e JOIN departments d
ON (e.department_id = d.department_id);
```
| EMPLOYEE\_ID | LAST\_NAME | DEPARTMENT\_ID | LOCATION\_ID |
| :--- | :--- | :--- | :--- |
| 200 | Whalen | 10 | 1700 |
| 201 | Hartstein | 20 | 1800 |
| 202 | Fay | 20 | 1800 |
| 114 | Raphaely | 30 | 1700 |
| 119 | Colmenares | 30 | 1700 |
| 115 | Khoo | 30 | 1700 |
| 116 | Baida | 30 | 1700 |
| 117 | Tobias | 30 | 1700 |
| 118 | Himuro | 30 | 1700 |
| 203 | Mavris | 40 | 2400 |

```sql
-- Joins utilizando várias tabelas com a Cláusula ON

SELECT e.employee_id, j.job_title, d.department_name, l.city, l.state_province, l.country_id
FROM employees e
  JOIN jobs        j ON (e.job_id = j.job_id)
  JOIN departments d ON (e.department_id = d.department_id)
  JOIN locations   l ON (d.location_id = l.location_id)
ORDER BY e.employee_id;
```
| EMPLOYEE\_ID | JOB\_TITLE | DEPARTMENT\_NAME | CITY | STATE\_PROVINCE | COUNTRY\_ID |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 100 | President | Executive | Seattle | Washington | US |
| 101 | Administration Vice President | Executive | Seattle | Washington | US |
| 102 | Administration Vice President | Executive | Seattle | Washington | US |
| 103 | Programmer | IT | Southlake | Texas | US |
| 104 | Programmer | IT | Southlake | Texas | US |
| 105 | Programmer | IT | Southlake | Texas | US |
| 106 | Programmer | IT | Southlake | Texas | US |
| 107 | Programmer | IT | Southlake | Texas | US |
| 108 | Finance Manager | Finance | Seattle | Washington | US |
| 109 | Accountant | Finance | Seattle | Washington | US |

```sql
-- Incluindo condições adicionais a condição de Join na cláusula WHERE

SELECT e.employee_id, e.last_name, e.salary, e.department_id, d.department_name
FROM employees e JOIN departments d
ON  (e.department_id = d.department_id)
WHERE (e.salary BETWEEN 10000 AND 15000);

```
| EMPLOYEE\_ID | LAST\_NAME | SALARY | DEPARTMENT\_ID | DEPARTMENT\_NAME |
| :--- | :--- | :--- | :--- | :--- |
| 201 | Hartstein | 13000.00 | 20 | Marketing |
| 114 | Raphaely | 11000.00 | 30 | Purchasing |
| 204 | Baer | 10000.00 | 70 | Public Relations |
| 147 | Errazuriz | 12000.00 | 80 | Sales |
| 169 | Bloom | 10000.00 | 80 | Sales |
| 145 | Russell | 14000.00 | 80 | Sales |
| 146 | Partners | 13500.00 | 80 | Sales |
| 174 | Abel | 11000.00 | 80 | Sales |
| 148 | Cambrault | 11000.00 | 80 | Sales |
| 149 | Zlotkey | 10500.00 | 80 | Sales |

```sql
-- Incluindo condições adicionais a condição de Join utilizando AND

SELECT e.employee_id, e.last_name, e.salary, e.department_id, d.department_name
FROM employees e JOIN departments d
ON (e.department_id = d.department_id) AND
   (e.salary BETWEEN 10000 AND 15000);

```
| EMPLOYEE\_ID | LAST\_NAME | SALARY | DEPARTMENT\_ID | DEPARTMENT\_NAME |
| :--- | :--- | :--- | :--- | :--- |
| 201 | Hartstein | 13000.00 | 20 | Marketing |
| 114 | Raphaely | 11000.00 | 30 | Purchasing |
| 204 | Baer | 10000.00 | 70 | Public Relations |
| 147 | Errazuriz | 12000.00 | 80 | Sales |
| 169 | Bloom | 10000.00 | 80 | Sales |
| 145 | Russell | 14000.00 | 80 | Sales |
| 146 | Partners | 13500.00 | 80 | Sales |
| 174 | Abel | 11000.00 | 80 | Sales |
| 148 | Cambrault | 11000.00 | 80 | Sales |
| 149 | Zlotkey | 10500.00 | 80 | Sales |

```sql
-- Self Join Utilizando a Cláusula ON

SELECT empregado.employee_id "Id empregado", empregado.last_name "Sobrenome empregado",
       gerente.employee_id "Id gerente", gerente.last_name "Sobrenome gerente"
FROM employees empregado JOIN employees gerente
ON (empregado.manager_id = gerente.employee_id)
ORDER BY empregado.employee_id;

```

| Id empregado | Sobrenome empregado | Id gerente | Sobrenome gerente |
| :--- | :--- | :--- | :--- |
| 101 | Kochhar | 100 | King |
| 102 | De Haan | 100 | King |
| 103 | Hunold | 102 | De Haan |
| 104 | Ernst | 103 | Hunold |
| 105 | Austin | 103 | Hunold |
| 106 | Pataballa | 103 | Hunold |
| 107 | Lorentz | 103 | Hunold |
| 108 | Greenberg | 101 | Kochhar |
| 109 | Faviet | 108 | Greenberg |
| 110 | Chen | 108 | Greenberg |


### 20 Oracle SQL - Nonequijoins

- [recursos/Seção+11+-+Prática+Aula+2.sql](/recursos/Seção+11+-+Prática+Aula+2.sql)

#### Nonequijoins

- Realizando um JOIN quando a condição de ligação não é uma condição de igualdade.

![img.png](img/20_1_nonequijoins1.png)

```sql
-- Nonequijoins

SELECT   e.employee_id, e.salary, j.grade_level, j.lowest_sal, j.highest_sal
FROM     employees e 
  JOIN   job_grades j
     ON  NVL(e.salary,0) BETWEEN j.lowest_sal AND j.highest_sal
ORDER BY e.salary;
```

```sql

SELECT   e.employee_id, e.salary, j.grade_level, j.lowest_sal, j.highest_sal
FROM     employees e 
  JOIN   job_grades j
     ON  NVL(e.salary,0) >= j.lowest_sal AND 
         NVL(e.salary,0) <= j.highest_sal
ORDER BY e.salary;
```

| EMPLOYEE\_ID | SALARY | GRADE\_LEVEL | LOWEST\_SAL | HIGHEST\_SAL |
| :--- | :--- | :--- | :--- | :--- |
| 132 | 2100.00 | A | 1000.00 | 2999.00 |
| 128 | 2200.00 | A | 1000.00 | 2999.00 |
| 136 | 2200.00 | A | 1000.00 | 2999.00 |
| 135 | 2400.00 | A | 1000.00 | 2999.00 |
| 127 | 2400.00 | A | 1000.00 | 2999.00 |
| 182 | 2500.00 | A | 1000.00 | 2999.00 |
| 144 | 2500.00 | A | 1000.00 | 2999.00 |
| 140 | 2500.00 | A | 1000.00 | 2999.00 |
| 119 | 2500.00 | A | 1000.00 | 2999.00 |
| 131 | 2500.00 | A | 1000.00 | 2999.00 |


### **Resumo sobre Nonequijoins**

**O que são Nonequijoins?**  
Nonequijoins (ou "junções não igualitárias") são operações de `JOIN` em SQL onde a condição de ligação entre as tabelas **não** é baseada em igualdade (`=`), mas sim em outros operadores de comparação, como:  
- `>` (maior que)  
- `<` (menor que)  
- `>=` (maior ou igual)  
- `<=` (menor ou igual)  
- `BETWEEN` (intervalo)  
- `LIKE` (padrões de texto)  

---

**Quando usar?**  
São úteis para:  
1. **Comparar intervalos de valores**:  
   - Exemplo: Vincular produtos a faixas de preço em uma tabela de categorias.  
   ```sql
   SELECT p.nome_produto, c.categoria
   FROM produtos p
   JOIN categorias c ON p.preco BETWEEN c.preco_min AND c.preco_max;
   ```

2. **Relacionar dados hierárquicos**:  
   - Exemplo: Funcionários e seus níveis salariais em uma tabela de faixas.  

3. **Filtrar com condições complexas**:  
   - Exemplo: Clientes com datas de cadastro anteriores a um período específico em outra tabela.  

---

**Diferença para EQUIJOINS**  
- **EQUIJOIN**: Usa `=` para relacionar chaves primárias/estrangeiras (ex: `ON tabelaA.id = tabelaB.id`).  
- **NONEQUIJOIN**: Usa outros operadores para relações não exatas.  

**Cuidados:**  
- Pode gerar resultados inesperados se a condição não for bem definida.  
- Pode ser menos eficiente que equijoins em bancos de dados grandes.  

---

**Exemplo Prático (Oracle):**  
```sql
-- Relaciona funcionários com suas faixas salariais (sem igualdade)
SELECT e.nome, e.salario, f.nivel
FROM funcionarios e
JOIN faixas_salariais f ON e.salario BETWEEN f.salario_min AND f.salario_max;
``` 

Essa consulta retorna o nível de cada funcionário com base em onde seu salário se encaixa na tabela `faixas_salariais`.

### 21 Oracle SQL - INNER Joins

- [recursos/Seção+11+-+Prática+Aula+3.sql](/recursos/Seção+11+-+Prática+Aula+3.sql)

#### INNER Join

- No SQL ANSI:1999, o join entre duas tabelas que retorna somente as linhas onde a condição de ligação coincidem é chamado INNER join (a palavra INNER é opcional)

```sql
-- Join com a Cláusula ON

SELECT e.employee_id, j.job_title, d.department_name, l.city, l.state_province, l.country_id
FROM   employees e
  INNER JOIN jobs        j ON e.job_id = j.job_id
  INNER JOIN departments d ON d.department_id = e.department_id
  INNER JOIN locations   l ON d.location_id = l.location_id
ORDER BY e.employee_id;

SELECT e.employee_id, j.job_title, d.department_name, l.city, l.state_province, l.country_id
FROM   employees e
  JOIN jobs        j ON e.job_id = j.job_id
  JOIN departments d ON d.department_id = e.department_id
  JOIN locations   l ON d.location_id = l.location_id
ORDER BY e.employee_id;
```

| EMPLOYEE\_ID | JOB\_TITLE | DEPARTMENT\_NAME | CITY | STATE\_PROVINCE | COUNTRY\_ID |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 100 | President | Executive | Seattle | Washington | US |
| 101 | Administration Vice President | Executive | Seattle | Washington | US |
| 102 | Administration Vice President | Executive | Seattle | Washington | US |
| 103 | Programmer | IT | Southlake | Texas | US |
| 104 | Programmer | IT | Southlake | Texas | US |
| 105 | Programmer | IT | Southlake | Texas | US |
| 106 | Programmer | IT | Southlake | Texas | US |
| 107 | Programmer | IT | Southlake | Texas | US |
| 108 | Finance Manager | Finance | Seattle | Washington | US |
| 109 | Accountant | Finance | Seattle | Washington | US |

```sql
-- Utilizando Natural Joins

SELECT  department_id, department_name, location_id, city
FROM    departments
NATURAL INNER JOIN locations;

SELECT  department_id, department_name, location_id, city
FROM    departments
NATURAL JOIN locations;
```

| DEPARTMENT\_ID | DEPARTMENT\_NAME | LOCATION\_ID | CITY |
| :--- | :--- | :--- | :--- |
| 60 | IT | 1400 | Southlake |
| 50 | Shipping | 1500 | South San Francisco |
| 10 | Administration | 1700 | Seattle |
| 30 | Purchasing | 1700 | Seattle |
| 90 | Executive | 1700 | Seattle |
| 100 | Finance | 1700 | Seattle |
| 110 | Accounting | 1700 | Seattle |
| 120 | Treasury | 1700 | Seattle |
| 130 | Corporate Tax | 1700 | Seattle |
| 140 | Control And Credit | 1700 | Seattle |

```sql
-- JOIN com a Cláusula USING

SELECT e.employee_id, e.last_name, d.location_id, department_id, d.department_name
FROM employees e
  INNER JOIN departments d USING (department_id);
  
SELECT e.employee_id, e.last_name, d.location_id, department_id, d.department_name
FROM employees e
  JOIN departments d USING (department_id);
```

| EMPLOYEE\_ID | LAST\_NAME | LOCATION\_ID | DEPARTMENT\_ID | DEPARTMENT\_NAME |
| :--- | :--- | :--- | :--- | :--- |
| 200 | Whalen | 1700 | 10 | Administration |
| 201 | Hartstein | 1800 | 20 | Marketing |
| 202 | Fay | 1800 | 20 | Marketing |
| 114 | Raphaely | 1700 | 30 | Purchasing |
| 119 | Colmenares | 1700 | 30 | Purchasing |
| 115 | Khoo | 1700 | 30 | Purchasing |
| 116 | Baida | 1700 | 30 | Purchasing |
| 117 | Tobias | 1700 | 30 | Purchasing |
| 118 | Himuro | 1700 | 30 | Purchasing |
| 203 | Mavris | 2400 | 40 | Human Resources |


# INNER JOIN em SQL

## 📌 O que é INNER JOIN?
O **INNER JOIN** (ou simplesmente `JOIN`) é uma operação que combina registros de duas tabelas quando há valores correspondentes nas colunas especificadas.

## 🔍 Como funciona?
- Retorna **apenas** as linhas onde existe correspondência em AMBAS as tabelas
- Linhas sem correspondência são **excluídas** do resultado
- É o tipo de JOIN mais comum e eficiente

## ✍️ Sintaxe Básica
```sql
SELECT colunas
FROM tabela1
[INNER] JOIN tabela2 
    ON tabela1.coluna = tabela2.coluna;
```
> 💡 A palavra `INNER` é opcional - apenas `JOIN` produz o mesmo resultado

## 🏆 Quando usar?
Situações ideais:
- Relacionar pedidos com clientes
- Vincular produtos a categorias
- Consultar alunos matriculados em disciplinas

## 📊 Exemplo Prático (Oracle)

**Tabelas:**
```sql
-- Funcionários
CREATE TABLE funcionarios (
    id NUMBER,
    nome VARCHAR2(100),
    departamento_id NUMBER
);

-- Departamentos
CREATE TABLE departamentos (
    id NUMBER,
    nome VARCHAR2(100)
);
```

**Consulta:**
```sql
SELECT f.nome AS funcionario, 
       d.nome AS departamento
FROM funcionarios f
JOIN departamentos d 
    ON f.departamento_id = d.id;
```

**Resultado:**
| funcionario | departamento |
|-------------|--------------|
| João Silva  | TI           |
| Maria Souza | RH           |

## ⚖️ INNER JOIN vs OUTER JOIN
| Tipo         | Comportamento                          |
|--------------|----------------------------------------|
| INNER JOIN   | Apenas correspondências exatas         |
| LEFT JOIN    | Todas linhas da tabela esquerda        |
| RIGHT JOIN   | Todas linhas da tabela direita         |
| FULL JOIN    | Todas linhas de ambas tabelas          |

## 💡 Dicas Importantes
1. Use **aliases** para simplificar consultas
   ```sql
   SELECT f.nome, d.nome
   FROM funcionarios f
   JOIN departamentos d ON f.depto_id = d.id;
   ```

2. Pode juntar múltiplas tabelas:
   ```sql
   SELECT f.nome, d.nome, p.nome_projeto
   FROM funcionarios f
   JOIN departamentos d ON f.depto_id = d.id
   JOIN projetos p ON d.id = p.depto_id;
   ```

3. Evite a sintaxe legada (usando WHERE) - prefira o padrão ANSI

## ⚠️ Cuidados
- Colunas com valores `NULL` não serão pareadas
- Certifique-se que as colunas de junção têm tipos de dados compatíveis
- Em tabelas grandes, crie índices nas colunas de junção para melhor performance

## 🔄 Sintaxe Alternativa (Oracle)
```sql
-- Equivalente usando WHERE (não recomendado)
SELECT f.nome, d.nome
FROM funcionarios f, departamentos d
WHERE f.departamento_id = d.id;
```

> 📌 **Melhor prática**: Sempre use a sintaxe explícita `JOIN...ON` para maior clareza e manutenibilidade do código.

## 🚀 Vantagens do INNER JOIN
- **Performance**: Geralmente mais rápido que OUTER JOINs
- **Precisão**: Retorna apenas dados relacionados
- **Legibilidade**: Facilita o entendimento das relações entre tabelas


### 22 Oracle SQL - OUTER Joins

- [recursos/Seção+11+-+Prática+Aula+4.sql](/recursos/Seção+11+-+Prática+Aula+4.sql)

#### OUTER Join

- Retornando Registros que não correspondem a condição de JOIN Utilizando OUTER Join

#### LEFT OUTER Join

- Um join entre duas tabelas que retorna as linhas que resultam do INNER join e também as linhas que não coincidem a partir da tabela LEFT é chamado de LEFT OUTER Join

```sql
-- LEFT OUTER JOIN

SELECT e.first_name, e.last_name, d.department_id, d.department_name
FROM employees e LEFT OUTER JOIN departments d
     ON (e.department_id = d.department_id) 
ORDER BY d.department_id;
```

| FIRST\_NAME | LAST\_NAME | DEPARTMENT\_ID | DEPARTMENT\_NAME |
| :--- | :--- |:---------------|:-----------------|
| Jennifer | Whalen | 10             | Administration   |
| Michael | Hartstein | 20             | Marketing        |
| Pat | Fay | 20             | Marketing        |
| Den | Raphaely | 30             | Purchasing       |
| Alexander | Khoo | 30             | Purchasing       |
| Shelli | Baida | 30             | Purchasing       |
| Sigal | Tobias | 30             | Purchasing       |
| Guy | Himuro | 30             | Purchasing       |
| Karen | Colmenares | 30             | Purchasing       |
| Susan | Mavris | (null)              | (null)           |


-- RIGHT OUTER JOIN

SELECT d.department_id, d.department_name, e.first_name, e.last_name
FROM employees e RIGHT OUTER JOIN departments d
     ON (e.department_id = d.department_id) 
ORDER BY d.department_id;



| DEPARTMENT\_ID | DEPARTMENT\_NAME | FIRST\_NAME | LAST\_NAME |
| :--- | :--- | :--- | :--- |
| 10 | Administration | Jennifer | Whalen |
| 20 | Marketing | Pat | Fay |
| 20 | Marketing | Michael | Hartstein |
| 30 | Purchasing | Sigal | Tobias |
| 30 | Purchasing | Karen | Colmenares |
| 30 | Purchasing | Shelli | Baida |
| 30 | Purchasing | Den | Raphaely |
| 30 | Purchasing | Alexander | Khoo |
| 30 | Purchasing | (null)  | (null)  |
| 40 | Human Resources | (null)  | (null)  |

```sql
-- FULL OUTER JOIN

SELECT d.department_id, d.department_name, e.first_name, e.last_name
FROM   employees e FULL OUTER JOIN departments d
     ON (e.department_id = d.department_id) 
ORDER BY d.department_id;
```

| DEPARTMENT\_ID | DEPARTMENT\_NAME | FIRST\_NAME | LAST\_NAME |
| :--- |:-----------------|:------------|:-----------|
| 10 | Administration   | Jennifer    | Whalen     |
| 20 | Marketing        | Pat         | Fay        |
| 20 | Marketing        | Michael     | Hartstein  |
| 30 | Purchasing       | Sigal       | Tobias     |
| 30 | Purchasing       | Shelli      | Baida      |
| 30 | Purchasing       | Karen       | Colmenares |
| 30 | <null>           | Guy         | Himuro     |
| 30 | Purchasing       | Den         | Raphaely   |
| 30 | Purchasing       | Alexander   | Khoo       |
| 40 | Human Resources  | <null>      | <null>     |


### 23 Oracle SQL - Produto Cartesiano

- [recursos/Seção+11+-+Prática+Aula+5.sql](/recursos/Seção+11+-+Prática+Aula+5.sql)

![img.png](img/23_1_cartesiano.png)

#### Gerando um Produto Cartesiano utilizando Cross Join

- A Cláusula CROSS JOIN produz um produto Cartesiano entre as duas tabelas.

```sql
-- Gerando um Produto Cartesiano utilizando Cross Join

SELECT last_name, department_name
FROM   employees
  CROSS JOIN departments;
```
| LAST\_NAME | DEPARTMENT\_NAME |
| :--- | :--- |
| Abel | Administration |
| Ande | Administration |
| Atkinson | Administration |
| Austin | Administration |
| Baer | Administration |
| Baida | Administration |
| Banda | Administration |
| Bates | Administration |
| Bell | Administration |
| Bernstein | Administration |

---

# CROSS JOIN no Oracle Database

## 📌 O que é CROSS JOIN?

O **CROSS JOIN** é um tipo de operação de junção em SQL que produz o **produto cartesiano** entre duas tabelas. No Oracle Database, assim como em outros SGBDs, ele combina cada linha da primeira tabela com todas as linhas da segunda tabela.

## 🔍 Como funciona?

- **Produto Cartesiano**: Combinação linear de todas as linhas
  - Se a tabela A tem *m* linhas e a tabela B tem *n* linhas
  - O resultado terá *m × n* linhas
- **Não requer** condição de junção (não usa ON ou USING)
- **Sintaxe básica**:
  ```sql
  SELECT colunas
  FROM tabela1
  CROSS JOIN tabela2;
  ```

## 💡 Casos de Uso Comuns

1. **Geração de dados combinatórios**:
   ```sql
   -- Combina cores com tamanhos para gerar todas variações
   SELECT c.cor, t.tamanho
   FROM cores c
   CROSS JOIN tamanhos t;
   ```

2. **Criação de datasets completos** para relatórios

3. **Testes de performance** (geração de massa de dados)

## ⚠️ Cuidados Importantes

1. **Impacto de performance**:
   - Tabelas com 1.000 linhas cada → 1.000.000 de resultados
   - Pode consumir recursos excessivos

2. **Uso consciente**:
   - Evite em tabelas grandes
   - Considere filtros adicionais (WHERE)

## 🆚 Comparação com outros JOINs

| Tipo         | Descrição                          | Oracle Syntax Example             |
|--------------|-----------------------------------|-----------------------------------|
| INNER JOIN   | Apenas linhas correspondentes     | `SELECT ... FROM A JOIN B ON...`  |
| LEFT JOIN    | Todas da esquerda + correspondentes | `SELECT ... FROM A LEFT JOIN B...`|
| CROSS JOIN   | Todas combinações possíveis        | `SELECT ... FROM A CROSS JOIN B`  |

## 🔄 Sintaxes Alternativas no Oracle

1. **Padrão ANSI** (recomendado):
   ```sql
   SELECT *
   FROM departamentos
   CROSS JOIN funcionarios;
   ```

2. **Sintaxe tradicional** (sem WHERE):
   ```sql
   SELECT *
   FROM departamentos, funcionarios;
   ```

## 📊 Exemplo Prático

```sql
-- Tabelas de exemplo
CREATE TABLE meses (
    mes_num NUMBER,
    mes_nome VARCHAR2(20)
);

CREATE TABLE anos (
    ano NUMBER
);

-- CROSS JOIN para gerar calendário
SELECT a.ano, m.mes_num, m.mes_nome
FROM anos a
CROSS JOIN meses m
ORDER BY a.ano, m.mes_num;
```

## 🚀 Boas Práticas

1. **Use com moderação** em tabelas pequenas
2. **Combine com WHERE** para limitar resultados:
   ```sql
   SELECT p.produto, r.regiao
   FROM produtos p
   CROSS JOIN regioes r
   WHERE r.regiao IN ('Norte', 'Sul');
   ```
3. **Prefira a sintaxe explícita** `CROSS JOIN` para maior clareza

> ⚠️ **Atenção**: Em implementações Oracle, o CROSS JOIN pode ser menos eficiente que outros joins para grandes volumes de dados. Sempre avalie o plano de execução.


### 24 Oracle SQL - Joins utilizando sintaxe Oracle




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

