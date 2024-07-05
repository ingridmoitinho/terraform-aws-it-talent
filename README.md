# Hands-On: Instalação do Terraform e criação de .TF para subir um EC2 e um S3 - IT TALENT 2024

## Objetivo
Aprender a instalar o Terraform, configurar um arquivo .tf (Terraform script) e provisionar uma instância EC2 e um bucket S3 utilizando o plano gratuito (freetier) da AWS.

## Pré-requisitos
- Conta AWS: Certifique-se de ter uma conta na AWS. Se ainda não possui, crie uma em AWS Free Tier.
- AWS CLI: Configure o AWS CLI em sua máquina para autenticação. Guia de instalação do AWS CLI.
- Credenciais da AWS: Configure suas credenciais executando aws configure no terminal após a instalação do AWS CLI.

## Passos
1. Instalação do Terraform no WSL Ubuntu
2. Configuração do Projeto Terraform e Criação do Arquivo de Configuração main.tf
3. Definir a Instância EC2
4. Criar um Bucket S3
5. Executar o Terraform
6. Verificar a Criação no Console AWS
7. Limpeza dos Recursos

## Entregáveis
- A inicialização do Terraform ( terraform init )
![Imagem1](https://github.com/ingridmoitinho/terraform-aws-it-talent/blob/main/prints/1%20terraform.png)

- O plano de execução do Terraform ( terraform plan ).
![Imagem2](https://github.com/ingridmoitinho/terraform-aws-it-talent/blob/main/prints/2%20terraform%20plan%20.png)
![Imagem3](https://github.com/ingridmoitinho/terraform-aws-it-talent/blob/main/prints/3%20terraform%20plan.png)

- A aplicação do plano ( terraform apply ).
![Imagem4](https://github.com/ingridmoitinho/terraform-aws-it-talent/blob/main/prints/4%20terraform%20apply.png)
![Imagem5](https://github.com/ingridmoitinho/terraform-aws-it-talent/blob/main/prints/5%20terraform%20apply.png)

- A verificação da instância EC2 e do bucket S3 no Console da AWS.
 ![Imagem6](https://github.com/ingridmoitinho/terraform-aws-it-talent/blob/main/prints/6%20ec2.png)
 ![Imagem7](https://github.com/ingridmoitinho/terraform-aws-it-talent/blob/main/prints/7%20s3.png)

## Link do Repositório no GitHub: 
- Compartilhe o link do repositório no GitHub onde o arquivo main.tf está armazenado: https://github.com/ingridmoitinho/terraform-aws-it-talent/blob/main/main.tf

