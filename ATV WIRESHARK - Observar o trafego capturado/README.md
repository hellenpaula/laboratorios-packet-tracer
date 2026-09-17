# 🔎 Análise de Tráfego de Rede com Wireshark

Atividade prática desenvolvida durante o curso **Dispositivos de Rede e Configuração Inicial**, do programa **Mulher Digital**, utilizando o Wireshark para analisar o tráfego ARP em uma rede local.

## 🎯 Objetivo

* Capturar e filtrar pacotes ARP;
* Identificar endereços IPv4 e MAC;
* Observar solicitações e respostas ARP;
* Consultar o cache ARP do computador.

## 🧪 Prática Realizada

Durante a atividade, foram utilizados os comandos:

```bash
ipconfig /all
ping 192.168.1.1
arp -a
```

No Wireshark, foi aplicado o filtro:

```text
arp
```

Em seguida, foram analisados pacotes ARP Request e ARP Reply, observando os endereços MAC, endereços IPv4 e o uso de broadcast na rede local.

## 📷 Evidências

### Tráfego ARP capturado

<img src="IMAGEM TOTAL COM PACOTES + DETALHES DO PACOTE + DADOS.png" alt="Lista de pacotes ARP">

### Detalhes de um pacote ARP

<img src="IMAGEM DETALHES DO PACOTE.png" alt="Pacote ARP analisado">

## 🧠 O que Aprendi

A atividade permitiu compreender como o protocolo ARP relaciona endereços IPv4 a endereços MAC para possibilitar a comunicação dentro de uma rede local.

Também pratiquei a captura e análise de pacotes no Wireshark e a consulta da tabela ARP pelo Prompt de Comando.

## 📁 Arquivos

* `README.md` — documentação da atividade;
* `images/` — imagens utilizadas como evidência;
* `trafego arp capturado note 3.pcapng` — arquivo de captura, caso disponibilizado.
