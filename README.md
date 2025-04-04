# Validação de Estoques VD+/VF

Este projeto é uma aplicação Flet para validar dados de estoque entre o VD+ e o Varejo Fácil.  Ele compara os dados de dois arquivos Excel (.xlsx) e gera um relatório com as diferenças encontradas.

## Funcionalidades:

* Seleção de arquivos VD+ e Varejo Fácil (.xlsx).
* Leitura dos arquivos Excel usando Pandas.
* Comparação de dados de estoque.
* Geração de um relatório Excel com três abas:
    * Itens Divergentes: Itens com diferença de estoque.
    * Estoque Sem Divergência: Itens com estoque igual em ambos os sistemas.
    * Validação de Estoque: Todos os itens com as informações de estoque.
* Abertura automática do relatório após a validação.

## Pré-requisitos:

* Python 3.x
* Flet
* Pandas
* openpyxl
* Git (recomendado)

## Instalação:

1. Clone o repositório: `git clone <repositório_git>` (se aplicável)
2. Crie um ambiente virtual: `python -m venv .venv`
3. Ative o ambiente virtual: `.venv\Scripts\activate` (Windows) ou `source .venv/bin/activate` (Linux/macOS)
4. Instale as dependências: `pip install -r requirements.txt`
5. Execute o aplicativo: `flet run`

## Uso:

1. Selecione os arquivos VD+ e Varejo Fácil usando os botões "Buscar Arquivo".
2. Clique em "Executar" para iniciar a validação.
3. O relatório será gerado e aberto automaticamente.

## Logs:

Os logs da aplicação são salvos no arquivo `app.log`.

## Contribuições:

Contribuições são bem-vindas!  Abra um issue ou um pull request.

## Licença:

[Adicione a sua licença aqui]