# Projeto de Chatbot com Flask

## Descrição

Este projeto é um chatbot simples implementado com Flask, que responde a perguntas pré-definidas. O chatbot é capaz de reconhecer algumas expressões comuns e fornecer respostas apropriadas. Além disso, ele permite que o usuário saia do chat de maneira amigável.

## Funcionalidades

- Respostas automatizadas a perguntas frequentes.
- Saída amigável quando o usuário deseja encerrar o chat.
- Interface web simples, acessível através de um navegador.

## Requisitos

Antes de executar o projeto, você precisará ter o Python instalado em seu sistema. O projeto também requer algumas bibliotecas que podem ser instaladas via pip.

### Bibliotecas Necessárias

- Flask
- Unidecode

***Você pode instalar as dependências necessárias executando:***
    ```bash
    pip install Flask unidecode
## Executando o Projeto

Para executar o projeto, siga estas etapas:

1. Clone o repositório ou faça o download dos arquivos do projeto.
2. Navegue até a pasta onde o arquivo `app.py` está localizado.
3. Execute o seguinte comando no terminal:

    ```bash
    python app.py
    ```

4. O aplicativo será iniciado e estará disponível em `http://127.0.0.1:5000`. Abra este URL em um navegador para interagir com o chatbot.

## Criando um Executável

Para criar um executável do projeto, você pode usar o PyInstaller. Siga os passos abaixo:

1. Instale o PyInstaller se ainda não o tiver:

    ```bash
    pip install pyinstaller
    ```

2. Navegue até a pasta do projeto no terminal e execute o seguinte comando:

    ```bash
    pyinstaller --onefile --add-data "templates;templates" app.py
    ```

3. Após a execução, um executável será gerado na pasta `dist`.

4. Para executar o aplicativo a partir do executável, você pode simplesmente clicar duas vezes no arquivo `app.exe` (no Windows) ou executar o arquivo `app` (em Linux/Mac) na pasta `dist`.



### Como Usar o README

1. **Personalize**: Adapte as seções de acordo com o que você deseja destacar sobre seu projeto.
2. **Formato Markdown**: Salve o arquivo como `README.md` para que seja renderizado corretamente no GitHub ou em outros repositórios que suportam Markdown.

Se precisar de mais alguma alteração ou adicionar algo específico, me avise!
