# Chatbot com IA

Este projeto é um chatbot simples em Python usando Streamlit e a API da OpenAI.

## Arquivos

- `main.py`: aplicação principal que cria a interface do chatbot e envia mensagens para a OpenAI.

## Pré-requisitos

- Python 3.10+ instalado
- `streamlit`
- SDK `openai` compatível com o pacote `openai` do Python

## Como usar

1. Clone ou copie o projeto para sua máquina.
2. Instale as dependências:

```bash
pip install streamlit openai
```

3. Abra `main.py` e substitua `INSIRA_SUA_CHAVE_DE_API_AQUI` pela sua chave da OpenAI.
4. Execute a aplicação:

```bash
streamlit run main.py
```

5. Abra o endereço exibido no terminal (geralmente `http://localhost:8501`).

## Funcionamento

- O usuário insere uma mensagem no campo de chat.
- A mensagem é armazenada no estado da sessão do Streamlit.
- O bot envia o histórico de conversas para o modelo `gpt-4o` da OpenAI.
- A resposta do modelo é exibida na interface.

## Observações

- Certifique-se de usar uma chave de API válida da OpenAI.
- O projeto não trata erros de rede ou limites da API, então use com cuidado.
