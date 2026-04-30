# ☁️ Laboratório Prático: Gerenciamento de Instâncias EC2 na AWS

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![EC2](https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white)

## 📌 Sobre o Desafio
Este repositório documenta a conclusão do desafio prático de **Gerenciamento de Instâncias EC2 na AWS** realizado através da plataforma [DIO](https://www.dio.me/). O projeto consistiu no provisionamento, configuração de segurança e acesso remoto a um servidor em nuvem.

## 🎯 Objetivos Alcançados
- [x] Criação de chaves de segurança (Key Pairs).
- [x] Configuração de regras de Firewall (Security Groups).
- [x] Provisionamento de instância com Amazon Linux 2023.
- [x] Conexão remota via SSH/EC2 Instance Connect.

## 🛠️ Passo a Passo da Implementação

### 1. Criação do Par de Chaves (Key Pair)
Iniciei o processo criando a chave de segurança `chavee-dio` no formato `.pem`.
![Key Pair](./key-pair.png)

### 2. Configurações de Rede e Segurança
Configurei o Security Group para permitir o tráfego SSH, restringindo o acesso apenas ao meu endereço IP atual.
![Network Settings](./network-settings.png)

### 3. Lançamento da Instância
O processo de lançamento foi concluído com sucesso, provisionando a infraestrutura na nuvem da AWS.
![Launching](./launching.png)
![Success](./success.png)

### 4. Conexão e Acesso ao Terminal
Após a inicialização, utilizei o **EC2 Instance Connect** para acessar o terminal e interagir com o sistema operacional Amazon Linux 2023.
![Terminal](./terminal.png)

## 💡 Insights e Aprendizados
1. **Segurança:** A importância de restringir portas de acesso (SSH) apenas para IPs autorizados.
2. **Praticidade:** A agilidade em subir um servidor configurado e pronto para uso em minutos.
3. **Documentação:** O uso do GitHub para registrar processos técnicos de forma estruturada.

---
*Projeto realizado para a Formação AWS da DIO.*
