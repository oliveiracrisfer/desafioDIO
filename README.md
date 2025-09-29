# Desafio de Modelagem de Banco de Dados

Este projeto faz parte de um desafio de modelagem conceitual de banco de dados.  

## 🔹 Requisitos atendidos
- **Conta PF e PJ**: Uma conta pode ser de Pessoa Física ou Jurídica, mas não ambas.  
- **Pagamento**: Uma conta pode ter múltiplas formas de pagamento cadastradas.  
- **Entrega**: Possui status e código de rastreio.  

## 🔹 Modelo Conceitual
Abaixo está o diagrama com a estrutura proposta:

![Modelo Conceitual](diagramas/modelo-conceitual.png)

## 🔹 Entidades
- **Conta**: entidade genérica para cadastro.  
- **PessoaFísica**: especialização de Conta, com CPF e nome completo.  
- **PessoaJurídica**: especialização de Conta, com CNPJ e razão social.  
- **Pagamento**: permite múltiplos cadastros por conta.  
- **Entrega**: possui status e código de rastreio.  
