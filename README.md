# Nunes Sports - CRUD de Produtos

Este é um projeto desenvolvido para o desafio Everymind - Best Minds 2024.2, que implementa um sistema CRUD para a empresa fictícia Nunes Sports. O sistema permite a criação, exibição, edição e deleção de produtos vendidos pela companhia.

## Tecnologias Utilizadas

- **Backend**: Python (Flask)
- **Banco de Dados**: SQLite
- **Frontend**: HTML, JavaScript (integrado ao Flask)
- **IDE**: Jupyter Notebook

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **Banco de Dados (SQLite)**: O banco de dados é utilizado para armazenar os produtos com os seguintes campos:
  - Nome do produto
  - Código do produto
  - Descrição do produto
  - Preço do produto

- **API (Flask)**: Uma API RESTful simples foi desenvolvida com Flask para realizar as operações CRUD (Create, Read, Update, Delete) nos produtos.

- **Frontend**: O frontend é uma página HTML simples que se comunica com a API Flask para realizar as operações no banco de dados.

## Requisitos para Execução

- Python 3.x
- Flask
- Jupyter Notebook

## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone <URL do repositório>
   cd <nome do repositório>
