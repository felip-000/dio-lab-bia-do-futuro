# Passo a Passo de Execução

Esta pasta contém o código do seu agente financeiro.

## Setup do Ollama

```bash
# 1. Instalar Ollama (ollama.com)
# 2. Baixar um modelo leve, ou usar um de cloud
ollama pull gpt-oss:20b-cloud

# 3. Testar se funciona
ollama run gpt-oss:20b-cloud "Olá!"
```

## Código Completo

Todo o código-fonte está no arquivo `app.py`.

## Como Rodar

```bash
# 1. Instalar dependências
pip install streamlit pandas requests

# 2. Garantir que o Ollama está rodando
ollama serve

# 3. Rodar o app
streamlit run .\src\app.py
```

## Evidência de execução 

<img width="1359" height="577" alt="image" src="https://github.com/user-attachments/assets/4382400e-34c7-4596-8ddb-37895a525921" />
