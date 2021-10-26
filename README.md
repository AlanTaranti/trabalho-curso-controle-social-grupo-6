# Trabalho de Conformidade do Curso de Dados Abertos para Controle Social


## O que é esse o projeto?

O objetivo do presente trabalho é verificar quais empresas de pessoas politicamente expostas que receberam recursos dos próprios municípios em que têm mandatos.

Para isso serão utilizados os dados do Portal de Transparência Municipal do TCESP, base de dados públicos de CNPJ da SRF e dados do Portal da Transparência da CGU.

**Atenção:** Como o presente trabalho é para fins educacionais, os nomes, CPFs e CNPJs foram alterados, mas as estruturas são idênticas às das tabelas originais.


## Como inicializar o projeto?

1. Primeiramente, tenha certeza que você tenhas os requisitos abaixos atendidos:

    - Python3+
    - Windows, Linux ou Mac

2. Crie um ambiente virtual

    ```
    python3 -m venv venv
    ```

3. Ative o ambiente virtual

    - Linux e MAC:
        ```
        . venv/bin/activate
        ```

    - Windows:
        ```
        env\Scripts\activate
        ```
4. Instale as dependencias

    ```
    pip install -r requirements.txt
    ```

5. Inicie o Jupyter Lab

    ```
    jupyter-lab
    ```

6. Pronto, pode explorar.

## Diretórios

Em `dados` ficam os dados disponiveis originais, e em `saida` ficam os dados modificados e/ou gerados.

