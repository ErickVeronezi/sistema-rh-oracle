# 📁 Projeto Oracle – Sistema de Recursos Humanos (RH)

Este projeto tem como objetivo demonstrar um sistema completo de Recursos Humanos utilizando Oracle SQL. Ele abrange desde a criação de tabelas e relações, até o uso de `TRIGGERS`, `PROCEDURES`, `VIEWS`, `PACKAGES` e simulações de testes.

🔗 Repositório: [https://github.com/ErickVeronezi](https://github.com/ErickVeronezi)

---

## 📌 Estrutura do Projeto

- **Tabelas**: Estruturadas com normalização e separadas por `TABLESPACE`.
- **Relacionamentos**: Com `FOREIGN KEY`, `CHECK`, `NOT NULL` e outras `CONSTRAINTS`.
- **Inserts de Exemplo**: Dados simulados para testes.
- **Triggers**:
  - Backup antes de DELETE.
  - Logs de login.
  - Controle de CPF e salário.
  - Histórico de mudanças salariais.
  - Registro automático e manual de ponto.
- **Procedures**:
  - Cadastro de funcionários.
  - Atualização de salário/cargo.
  - Registro de férias.
  - Bônus salarial.
  - Cálculo da média salarial de departamentos.
- **Packages**:
  - Encapsulamento de lógica de funcionários.
- **Views**:
  - Relatórios gerenciais e operacionais.
- **Testes**:
  - Arquivo com todos os testes das `PROCEDURES`, `VIEWS` e `PACKAGES`.

---

## 📂 Arquivos do Projeto

| Arquivo | Descrição |
|--------|-----------|
| `create_tablespace_tables.sql` | Criação das tablespaces e tabelas |
| `constraints.sql` | Definições de restrições (PK, FK, CHECK, UNIQUE...) |
| `inserts_exemplo.sql` | Inserts com dados simulados para testes |
| `triggers.sql` | Triggers de segurança, auditoria e backup |
| `procedures.sql` | Procedures com regras de negócio |
| `packages.sql` | Pacote com lógica de cadastro e consulta |
| `views.sql` | Criação de views gerenciais |
| `testes.sql` | Simulações de uso de procedures, views e pacote |
| `Diagrama.jpg` | Modelo relacional do projeto |

---

## 📊 Relatórios (VIEWS)

- `V_RELATORIO_FUNCIONARIO`
- `V_RELATORIO_ENDERECO`
- `V_RELATORIO_COMPLETO`
- `V_PONTO_FUNCIONARIO`
- `V_FERIAS_APROVADAS`
- `V_FUNCIONARIOS_DEPENDENTES`
- `V_HISTORICO_FUNCIONARIO`

---

## ⚙️ Funcionalidades (Procedures)

- Bater ponto manualmente.
- Aplicar bônus salarial.
- Atualizar salário ou cargo de um funcionário.
- Cadastrar funcionários via procedure.
- Registrar férias aprovadas.
- Calcular a média salarial de um departamento.

---

## 📦 Package: `PKG_FUNCIONARIO`

Funções encapsuladas:

- `CADASTRAR(...)`
- `ATUALIZAR_SALARIO(...)'

---

## 🧪 Testes

O arquivo `testes.sql` contém:

- Execução de procedures com `EXEC`.
- Verificação das `VIEWS` com `SELECT *`.
- Testes do pacote com chamadas diretas.

---

## 📌 Observações

- Projeto voltado para fins **educacionais**, utilizando **boas práticas** de modelagem e organização em Oracle.
- Desenvolvido como parte de uma **simulação prática** para portfólio.

---

## 👨‍💻 Autor

- **Erick Veronezi**  
- 💼 Estudante de Sistemas de Informação  
- 🔗 [github.com/ErickVeronezi](https://github.com/ErickVeronezi)

---

