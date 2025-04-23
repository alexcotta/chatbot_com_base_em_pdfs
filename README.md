# Projeto Chatbot com base em PDFs

Este projeto consiste em um chatbot com base no chatgpt capaz de ler e interpretar documentos em formato PDF.
 E responder perguntas baseadas no conteúdo desses arquivos. 
 
 Utilizando técnicas de processamento de linguagem natural (NLP) e extração de texto, o chatbot automatiza a busca por informações relevantes dentro de documentos 
 e possibilita o usuário realizar perguntas sobre os conteúdos aprendidos.
 
## Tecnologias Usadas

- Chatgpt GPT-4


# Perguntas e Respostas com Fontes Citadas

## 1. Quais são as etapas de um pipeline de dados?

As etapas típicas de um pipeline de dados seguem o processo conhecido como **ETL (Extract, Transform, Load)**:

1. **Extração (Extract):** coleta de dados de diferentes fontes, como bancos de dados, APIs, arquivos, etc.
2. **Transformação (Transform):** limpeza, agregação e padronização dos dados para adequação ao sistema de destino.
3. **Carga (Load):** inserção dos dados transformados em um repositório final (ex.: Data Warehouse).
4. **Automação e Orquestração:** uso de ferramentas para agendamento e gerenciamento de tarefas, como Apache Airflow, Luigi, ou ferramentas específicas que integram geração de código via inteligência artificial.
5. **Validação e Monitoramento:** execução de testes e monitoramento para garantir a integridade dos dados e identificar eventuais falhas no processo.

No documento *"Abordagem de desenvolvimento de uma pipeline de migração de dados utilizando inteligência artificial"* essas etapas são automatizadas usando modelos de linguagem (como GPT-4 e Gemini) e frameworks (como LangChain) para gerar os scripts de SQL e Python de forma automatizada a partir de inputs em linguagem natural.  
- Fonte: "Abordagem de desenvolvimento de uma pipeline de migração de dados utilizando inteligência artificial"

---

## 2. O que é uma migração de dados?

**Migração de dados** é o processo de **transferir dados de um sistema para outro**, podendo envolver mudanças de localização, formato ou tecnologia. Esse processo é comum em cenários como:

- Atualizações de sistemas legados para novos sistemas.
- Mudança de banco de dados (ex.: de MySQL para PostgreSQL).
- Migração para a nuvem (de servidores locais para ambientes cloud).
- Integração entre sistemas diferentes.
- Construção de Data Warehouses ou Data Lakes.

No documento mencionado, essa abordagem é explorada com o auxílio de inteligência artificial para automatizar a geração de código que extrai, transforma e carrega os dados entre as bases, facilitando o processo e minimizando erros.  
- Fonte: "Abordagem de desenvolvimento de uma pipeline de migração de dados utilizando inteligência artificial"
