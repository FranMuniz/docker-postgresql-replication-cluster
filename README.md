# 🐘 Replicação em um cluster com PostgreSQL usando Docker

Este projeto é uma demonstração prática de **replicação de dados** utilizando **PostgreSQL** em containers Docker. A atividade foi realizada como parte da pós-graduação em Engenharia e Arquitetura de Dados, dentro do tema **Bancos de Dados Distribuídos e Técnicas Utilizadas para Distribuição de Dados**. Demonstra como configurar um ambiente de banco de dados distribuído com **PostgreSQL**, usando **replicação física** e **balanceamento de carga** via **Pgpool-II**.

## 📌 Objetivo

- Simular replicação de dados em múltiplos nós (Master + Réplicas)
- Demonstrar tolerância a falhas e distribuição de leitura com Pgpool-II
- Estudo prático sobre bancos de dados distribuídos

Assim, foi possível demonstrar como os dados são replicados entre os nós e como o sistema continua funcional mesmo com a queda de um nó.

## 🛠️ Arquitetura

- **Master**: `postgres`
- **Réplicas**: `postgres-replica-1`, `postgres-replica-2`
- **Load Balancer**: `pgpool`

## ⚙️ Tecnologias utilizadas

- PostgreSQL
- Docker & Docker Compose
- Pgpool-II
