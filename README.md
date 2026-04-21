# ☁️ Implementação de Infraestrutura AWS: Servidor Web com VPC

## 📝 Sobre o Projeto
Este laboratório foi realizado durante o programa **AWS re/Start (Escola da Nuvem)**. O objetivo foi projetar e implementar uma arquitetura de rede segura e resiliente na AWS para hospedar um servidor web.

## 🛠️ O que foi construído:
- **Rede Isolada:** Criação de uma VPC personalizada para garantir a segurança dos dados.
- **Alta Disponibilidade:** Distribuição em duas Zonas de Disponibilidade (AZs) para evitar quedas.
- **Segurança em Camadas:** Divisão entre subnets públicas (para o servidor) e privadas (para recursos sensíveis).
- **Conectividade:** Configuração de Internet Gateway para acesso externo e NAT Gateway para atualizações seguras.

## 📐 Diagrama da Arquitetura
Abaixo está o desenho técnico da infraestrutura que implementei:

![Diagrama da Arquitetura](./diagrama-do-cliente.png)

## ✅ Resultados
- Servidor Linux (EC2) rodando Apache com script de automação.
- Tabelas de roteamento configuradas para controle total do tráfego.
