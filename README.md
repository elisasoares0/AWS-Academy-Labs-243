# 🚀 Laboratório: Gerenciamento de Software e AWS CLI no Amazon Linux

Repositório criado para documentar as atividades práticas de administração de sistemas Linux e integração com os serviços da AWS, desenvolvidas durante a formação na **Escola da Nuvem**.

---

## 🎯 Objetivos do Laboratório
Neste laboratório, foram abordados os seguintes tópicos práticos:
* Atualização do sistema operacional Linux utilizando o gerenciador de pacotes `yum`.
* Auditoria e reversão (*rollback*) de pacotes utilizando o histórico de transações (`yum history`).
* Instalação manual e configuração da **AWS CLI (v2)** em uma instância Amazon EC2.
* Execução de chamadas diretas à API da AWS via terminal para inspecionar atributos de recursos.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Amazon Linux (EC2)** / Ambiente Linux
* **Yum Package Manager** (`yum`, `yum history`)
* **AWS CLI v2**
* **Git & GitHub**

---

## 📋 Passo a Passo Executado

### 1. Conexão SSH e Gerenciamento de Pacotes (`yum`)
* Conexão remota à instância Amazon EC2 via SSH utilizando chave PEM.
* Atualização controlada do sistema e aplicação de patches de segurança:
  ```bash
  sudo yum -y upgrade
  sudo yum install httpd -y
