# Visão Computacional com AWS Rekognition e OpenAI

Projeto desenvolvido para a disciplina de Cloud Computing & Machine as a Service.

## Objetivo

Criar uma aplicação capaz de analisar uma imagem utilizando um serviço de visão computacional em nuvem e gerar uma descrição textual da imagem.

## Tecnologias utilizadas

- Python
- AWS
- Amazon Rekognition
- OpenAI API
- Boto3

## Funcionamento

A aplicação envia uma imagem local para o Amazon Rekognition.

O Rekognition identifica objetos, pessoas, cenários e outros elementos presentes na imagem, retornando também o nível de confiança de cada detecção.

Os elementos identificados são enviados para a OpenAI API, que gera uma descrição da imagem em linguagem natural.

## Fluxo

Imagem → Amazon Rekognition → Labels → OpenAI API → Descrição

## Instalação

Instale as dependências:

```bash
pip install -r requirements.txt