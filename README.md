# DesafioAWS_CIoudFormation# 🚀 AWS CloudFormation - Primeira Stack

Este projeto tem como objetivo demonstrar a criação de uma infraestrutura básica na AWS utilizando CloudFormation, como parte do laboratório da DIO.

---

## 📚 Objetivo

Aprender a criar e gerenciar recursos de infraestrutura como código (IaC) utilizando AWS CloudFormation, entendendo como definir, provisionar e versionar recursos na nuvem.

---

## 🛠️ Tecnologias utilizadas

- AWS CloudFormation
- AWS Console
- YAML (ou JSON)
- GitHub

---

## 🧱 O que foi criado na Stack

Neste laboratório, foi criada uma Stack AWS contendo:

- Recursos básicos da infraestrutura (ex: S3, EC2 ou outros dependendo do seu lab)
- Configuração automatizada via template YAML
- Deploy realizado diretamente pelo console AWS

---

## 📄 Exemplo de Template (CloudFormation)

```yaml
AWSTemplateFormatVersion: '2010-09-09'
Description: Primeira stack CloudFormation

Resources:
  MeuBucketS3:
    Type: AWS::S3::Bucket
    Properties:
      BucketName: meu-bucket-dio-exemplo
