# Laboratório #02

Este laboratório apresenta a configuração de um cluster em Docker usando MySQL e MongoDB. O projeto aborda a replicação de dados entre servidores, a fragmentação de tabelas grandes e transações distribuídas (2PC), terminando com a migração para NoSQL face ao Teorema CAP.

## Estrutura do Laboratório
```text
bdd2-lab02-grupo[N]/
├── README.md                 ← descrição do projeto, como executar, conclusões
├── dados/
│   ├── mercadokwanza_p1.sql  ← dataset da Parte 1
│   └── mercadokwanza_p2.sql  ← dataset da Parte 2
├── scripts/
│   ├── transacao.py          ← script de transação distribuída
│   └── migracao.py           ← script de migração para MongoDB
├── docker-compose.yml        ← configuração do cluster
└── relatorio/
    └── Lab02_Grupo[N].pdf    ← relatório em PDF
```