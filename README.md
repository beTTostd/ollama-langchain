# ollama-langchain

Esse projeto é um projeto para experimentar o uso de LLM, ou Grande Modelo de Linguagem, em ambiente local usando [Ollama](https://ollama.com/) e [Python](https://www.python.org/) com [langchain](https://www.langchain.com/).

# Setup
Para esse projeto requer o [Ollama](https://ollama.com/) e [Python](https://www.python.org/) instalado.

O projeto também usa o [jupyter notebook](https://jupyter.org/), Desenvolvi usando a [extensão para o vscode](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter&ssr=false#overview).

Antes de começar, você deve baixar o modelo `llama3.2` executando o seguinte comando:
```
ollama run llama3.2
```

Para controle de depencencias estou utilizando o [pipenv](https://pipenv.pypa.io/en/latest/), basta executar o comando seguinte comando para instalar as dependencias.
```
pipenv shell
```