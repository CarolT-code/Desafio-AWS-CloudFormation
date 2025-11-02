# Desafio-AWS-CloudFormation
Desafio do Bootcamp Santander Code Girls 2025 

# Stack com AWS CloudFormation

Este repositório reúne anotações obtidas durante o curso sobre implementação dEa stack utilizando o AWS CloudFormation.  
O objetivo deste material é servir como apoio para estudos futuros e como referência para novas implementações na AWS utilizando infraestrutura como código.

---

## 1. O que é o AWS CloudFormation

AWS CloudFormation é um serviço que permite criar e gerenciar recursos de infraestrutura na AWS de forma automatizada, utilizando templates escritos em JSON ou YAML.  
Esses templates descrevem os recursos que devem ser criados, como EC2, VPC, Security Groups, Buckets S3, Load Balancers, entre outros.

Alguns pontos importantes:

- Permite automatizar a criação, modificação e exclusão de recursos.  
- Os templates podem ser reutilizados quantas vezes forem necessários.  
- O usuário paga apenas pelos recursos que o template cria, e não pelo CloudFormation.  
- Facilita padronização e versionamento da infraestrutura.  
- É possível validar (verificar) os templates antes da execução para garantir que a estrutura está correta.  
- Através do CloudFormation, podemos criar desde um recurso simples até uma arquitetura completa e robusta.

O fluxo básico é:

1. Escrever o template em JSON ou YAML.  
2. Validar o template.  
3. Enviar o template para o CloudFormation.  
4. O serviço cria uma *stack* contendo todos os recursos definidos.  
5. Podemos atualizar ou deletar a stack conforme necessidade.

---

## 2. Conceitos Fundamentais

### Template
Arquivo JSON/YAML que descreve recursos, parâmetros, variáveis, mapeamentos e saídas.

### Stack
Conjunto de recursos criados a partir de um template.

### Automação
Uma vez definido o template, toda criação de infraestrutura se torna automática e replicável.

### Verificação do template
O CloudFormation permite validar a estrutura do arquivo para evitar erros antes da criação da stack.

### Tags
Durante a criação da stack, podemos adicionar *tags* para organizar recursos, aplicar políticas e facilitar auditoria.

---

