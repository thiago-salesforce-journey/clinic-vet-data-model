# Clínica Veterinária — Modelagem de Dados

Este repositório documenta a modelagem de dados de um sistema para uma clínica veterinária, 
partindo de um **MER lógico tradicional** até sua **adaptação para o ecossistema Salesforce**.

## 🎯 Objetivo

Demonstrar:
- entendimento de regras de negócio
- modelagem entidade-relacionamento
- tomada de decisão técnica
- adaptação consciente para Salesforce

## 🧩 Contexto do Negócio

O sistema tem como objetivo gerenciar:
- clientes (tutores)
- animais
- consultas veterinárias
- profissionais e suas especialidades

A modelagem considera a realidade de clínicas de pequeno porte e sua possível evolução futura.

## 📂 Estrutura do Repositório

- `/mer`  
  Contém o modelo entidade-relacionamento lógico (agnóstico de tecnologia).

- `/salesforce-friendly`  
  Contém a versão adaptada para Salesforce, respeitando boas práticas da plataforma 
  e documentando decisões técnicas.

## 🔁 Evolução do Modelo

A adaptação para Salesforce **não substitui** o MER original.  
Ela representa uma evolução baseada em:
- limitações da plataforma
- simplicidade operacional
- foco em relatórios e manutenção
