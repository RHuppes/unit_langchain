# 🚀 Desafio DIO: Automatização da Criação de Testes Unitários com LangChain e Azure ChatGPT

## 📖 Descrição
Este projeto foi desenvolvido como parte do desafio da DIO, com o objetivo de **automatizar a geração de testes unitários** utilizando **LangChain** integrado ao **Azure ChatGPT**.  
A ideia é demonstrar como modelos de linguagem podem ser utilizados para acelerar o desenvolvimento de software, garantindo maior qualidade e cobertura nos testes.

## 🎯 Objetivos de Aprendizagem
- Aplicar conceitos de **Processamento de Linguagem Natural (PLN)** em um caso prático.
- Automatizar a criação de testes unitários a partir de código-fonte existente.
- Integrar o **LangChain** ao **Azure OpenAI (ChatGPT)**.
- Documentar de forma clara os processos técnicos.
- Utilizar o GitHub como ferramenta de versionamento e compartilhamento técnico.

## 🛠️ Tecnologias Utilizadas
- [Python](https://www.python.org/)  
- [LangChain](https://www.langchain.com/)  
- [Azure OpenAI Service](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/)  
- [Pytest](https://docs.pytest.org/) (ou unittest)  
- Git & GitHub  

## 🚀 Como Funciona
1. O usuário fornece um trecho de código Python.  
2. O sistema, via **LangChain + Azure ChatGPT**, gera automaticamente testes unitários sugeridos.  
3. Os testes são salvos em arquivos `.py` prontos para execução.  
4. O desenvolvedor executa `pytest` para validar os testes.  

### Exemplo
Código de entrada:
```
def soma(a, b):
    return a + b
```
Saída gerada automaticamente:
```
import pytest
from my_module import soma

def test_soma_inteiros():
    assert soma(2, 3) == 5

def test_soma_negativos():
    assert soma(-2, -3) == -5
```

📂 Estrutura do Repositório
├── README.md
├── src/
│   └── exemplo.py
├── tests/
│   └── test_exemplo.py
├── /images
│   ├── arquitetura.png
│   └── execução.png

📸 Evidências

Na pasta /images estão incluídas capturas de tela da execução do sistema, mostrando:

Arquitetura do fluxo LangChain + Azure

Geração automática de testes

Execução com Pytest

📑 Conclusão

Este projeto mostrou na prática como IA Generativa pode ser utilizada no desenvolvimento de software, trazendo velocidade e confiabilidade para a criação de testes unitários.
Além disso, consolidou o aprendizado em LangChain, Azure OpenAI e boas práticas de documentação técnica.
