
---

# 📡 Teste MQTT + MySQL – Integração de Comunicação e Banco de Dados

## 📌 Descrição

Projeto desenvolvido para estudo do **protocolo MQTT** em conjunto com **persistência em banco de dados MySQL**.

O objetivo foi simular a comunicação entre clientes e broker MQTT, publicando e assinando tópicos, e armazenar as mensagens recebidas em um banco de dados para consulta e análise posterior.

Este projeto serve como modelo de integração para aplicações IoT, monitoramento de dados em tempo real e sistemas que dependem de comunicação assíncrona entre dispositivos e backend.

---

## 🎯 Objetivo

* Compreender o funcionamento do protocolo MQTT
* Implementar comunicação assíncrona com broker
* Publicar e consumir mensagens em tópicos específicos
* Armazenar mensagens recebidas em banco de dados MySQL
* Criar modelo reutilizável para integrações futuras

---

## 🛠️ Tecnologias Utilizadas

* Java 
* Biblioteca MQTT
* Protocolo MQTT
* MySQL
* JDBC / Spring Data JPA (se aplicável)
* Git e GitHub

---

## 📡 Conceitos Aplicados

### 🔄 Publish / Subscribe

* Publicação de mensagens em tópicos MQTT
* Assinatura para receber mensagens
* Comunicação desacoplada entre emissor e receptor

### 🌐 Broker

* Conexão com broker MQTT
* Gerenciamento de sessão
* Controle de reconexão

### 💾 Persistência em Banco de Dados

* Conexão com MySQL
* Armazenamento de mensagens recebidas
* Consulta de dados para monitoramento e análise

### 🧱 Estrutura Modular

* Classe responsável pela conexão MQTT
* Classe responsável pela publicação
* Classe responsável pela assinatura
* Classe responsável pelo armazenamento em banco de dados

---

## ⚙️ Funcionalidades

* Conectar ao broker MQTT
* Publicar mensagens em tópico específico
* Assinar tópico e receber mensagens em tempo real
* Salvar mensagens no banco MySQL
* Encerrar conexão corretamente

---

## 🔧 Configuração

Exemplo de parâmetros:

* Broker URL: `tcp://localhost:8080`
* Banco de dados MySQL: `localhost:3306`
* Nome do banco: `mqtt_db`
* Usuário e senha do MySQL configurados no arquivo de conexão

---

## 📊 Possível Aplicação

* Sistemas IoT
* Monitoramento de sensores em tempo real
* Integração entre microserviços
* Aplicações que exigem registro persistente de mensagens

---

## 📘 Status

✔️ Projeto de estudo
📡 Modelo de integração MQTT + MySQL
🚀 Base para projetos futuros de comunicação e persistência

---

## 📎 Autora

**Gabrieli da Silva Marcelino**
Desenvolvimento de Sistemas | Interesse em Integração, IoT e Arquitetura de Software

---
