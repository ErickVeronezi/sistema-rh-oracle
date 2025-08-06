
# Estrutura de Pastas do Projeto - Banco de Dados Escola

Este projeto foi organizado com uma estrutura de pastas pensada para facilitar administração, evolução e reutilização do código em múltiplos SGBDs.

# Visão Geral

```
escola-db/
│
├── ddl/
│   │   ├── constraints.sql            # Constraints e foreign keys
│   │   ├── create_tablespace_tables.sql          # Criação das tabelas e tablespace
│   │   ├── exemplos_testes		# Dados de exemplo (EXECs de 'Views', 'Triggers' e 'Package'
│   │   ├── inserts_exemplo.sql        # Dados de exemplo (INSERTS)
│   │   ├── packages.sql 		# Criação de packages
│   │   ├── procedures.sql               # Criação de procedures
│   │   ├── triggers.sql                  # Criação de trigggers
│   │   ├── views.sql                  # Criação de Views para relatórios
│   │
│
├── diagramas/
│   ├── modelo_brmodelo.jpg     # Modelo lógico feito no BRModelo
│   ├── modelo_dbdiagram.png    # Modelo lógico feito no dbdiagram.io
│
├── doc/
│   └── estrutura_pastas.md            # (este arquivo)
```
---

Criado por Erick Veronezi – Projeto acadêmico para estudos com SQL e outros SGBDs.
