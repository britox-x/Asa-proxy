# Asa Proxy

O projeto **Asa Proxy** tem como objetivo implementar uma infraestrutura web utilizando Docker, com a configuração de um proxy reverso e dois servidores de aplicação, além de um servidor DNS primário para resolução direta de domínios. O sistema também inclui scripts de automação para a criação, exclusão, início e parada dos serviços.

## 🚀 Objetivo

Este repositório contém a infraestrutura completa de um servidor web utilizando Docker, com as seguintes configurações:

- **Proxy reverso** para gerenciar as requisições.
- **Dois servidores de aplicação** para lidar com as requisições passadas pelo proxy.
- **Servidor DNS primário** para resolver os domínios criados, utilizando uma zona de resolução direta.
- **Scripts de automação** para facilitar a criação e gerenciamento da infraestrutura.

## 📦 Tecnologias Utilizadas

- **Docker**: Para containerização e execução dos serviços.
- **NGINX**: Usado como proxy reverso para rotear as requisições para os servidores de aplicação.
- **BIND**: Servidor DNS primário responsável pela resolução de domínios.
- **Shell Scripts**: Para automatizar a criação, exclusão e gerenciamento dos serviços.
- **GitHub Actions**: Para automação de fluxos de trabalho.

## 🛠️ Como Usar

### 1. Clonando o Repositório

Clone este repositório em sua máquina local:

```bash
git clone https://github.com/britox-x/Asa-proxy.git
