
# 🌐 Laboratório 01 - Exploração dos Modos Logical e Physical

Laboratório realizado no **Cisco Packet Tracer** durante o curso **Começando Packet Tracer**, do programa Mulher Digital. A atividade teve como objetivo explorar uma rede empresarial nos modos Logical e Physical, realizar conexões entre dispositivos e configurar um roteador de backup.

---

## 📷 Preview

<img src="imagens/img Branch Office.png" alt="Topologia do laboratório" >

---

## 📋 Objetivos

- Explorar os modos **Logical** e **Physical**
- Identificar dispositivos e infraestrutura de rede
- Conectar dispositivos utilizando diferentes cabos
- Instalar um roteador de backup
- Configurar um **hostname** pela CLI

---

## 🌐 Sobre a Atividade

A atividade apresenta uma rede empresarial distribuída entre as cidades de **Seward** e **Warrenton**.

Durante a exploração, foram identificados:

- **Seward:** Branch Office
- **Warrenton:** Data Center e Teleworker
- **Cabo submarino:** Alaska United West (AU-West) Submarine Cable

### Logical x Physical

| Modo | Representação |
|---|---|
| **Logical** | Conexões e topologia lógica da rede |
| **Physical** | Localização física dos dispositivos e infraestrutura |

---

## 🔌 Atividades Realizadas

- Conexão do **PC_1 → ALS2** utilizando cabo Ethernet
- Conexão do **PC_1 → Edge_Router** utilizando cabo de console
- Instalação do **Backup_Router** no rack
- Conexão do **Laptop_1 → Backup_Router** utilizando cabo USB
- Acesso à CLI do roteador
- Configuração do hostname

### Configuração realizada

```text
Router> enable
Router# configure terminal
Router(config)# hostname Edge_Router_Backup
Edge_Router_Backup(config)# end
