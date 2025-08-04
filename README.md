

# 🚀 Plataforma de Automação e Análise de Vendas para Afiliados com IA e Voz 🚀

## ✨ Descrição do Projeto

Este projeto é uma plataforma inovadora desenvolvida em Python, focada em otimizar e automatizar processos de vendas para afiliados. A solução integra **Inteligência Artificial** (IA) e **processamento de voz** para transformar dados brutos de diversas fontes (tela, voz e APIs) em informações acionáveis e conhecimento valioso.

O principal objetivo é aprimorar a tomada de decisão e a eficiência operacional no nicho de marketing de afiliados, demonstrando proficiência em áreas-chave da **Engenharia de Dados**:

  * ✅ Desenvolvimento e manutenção de pipelines de dados.
  * ✅ Modelagem de Banco de Dados (relacional) para fins analíticos.
  * ✅ Execução de processos ETL (Extract, Transform, Load).
  * ✅ Desenvolvimento de consultas SQL otimizadas.
  * ✅ Conhecimento aprofundado em programação Python.
  * ✅ Adesão a boas práticas de engenharia de software.

## ⚙️ Arquitetura do Projeto

A arquitetura do projeto segue um fluxo de dados bem definido, abrangendo desde a ingestão de dados brutos até a geração de insights e automação. O diagrama abaixo ilustra o fluxo de dados e os componentes-chave:

### Componentes Chave:

  * **Fontes de Dados:** Captura de texto da **tela** (via OCR), comandos de **voz** (via Speech-to-Text), e dados de **APIs** de plataformas de afiliados (Hotmart) e redes sociais.
  * **Módulos de Ingestão e Pré-processamento:** Responsáveis por coletar e preparar os dados brutos para o processamento.
  * **LLM (Large Language Model):** A inteligência central para análise, recomendação de produtos e geração de respostas coerentes.
  * **Módulos ETL:** Processam e transformam os dados para que possam ser carregados e armazenados no banco de dados relacional.
  * **Banco de Dados Relacional:** O repositório centralizado onde os dados estruturados são armazenados.
  * **Consultas SQL:** Ferramenta para extrair informações detalhadas para análise e relatórios.
  * **Automação/Relatórios:** Geração de ações automatizadas e apresentação de insights valiosos.

## 🛠️ Funcionalidades Principais

### 🗣️ Leitura e Resposta Inteligente:

  * **Captura de Texto:** Utiliza OCR (Optical Character Recognition) para ler texto diretamente da tela.
  * **Processamento com IA:** Um LLM (Large Language Model) analisa o texto capturado para gerar respostas relevantes e contextuais.
  * **Automação de Respostas:** A plataforma automatiza a digitação das respostas na tela, agilizando a interação.

### 🎙️ Comandos de Voz e Automação:

  * **Reconhecimento de Fala:** Converte comandos de voz em texto (Speech-to-Text).
  * **Processamento por IA:** A inteligência artificial interpreta a intenção e os dados contidos nos comandos de voz para, por exemplo, registrar pedidos.
  * **Automação de Ações:** Executa ações e registra dados no banco de dados com base nos comandos de voz.

### 🛒 Gestão de Produtos Afiliados:

  * **Ingestão de Dados:** Simula a ingestão de dados de produtos de plataformas como a Hotmart via API.
  * **Recomendação com IA:** Sugere produtos para vendas utilizando IA, com base em dados de mercado e histórico.

### 📊 Análise de Vendas e Métricas:

  * **Armazenamento de Dados:** Armazena dados de produtos, interações e pedidos em um banco de dados relacional (PostgreSQL/MySQL).
  * **Análise com SQL:** Permite a execução de consultas SQL para análise de desempenho de produtos e tendências de pedidos.
  * **Análise de Engajamento:** Simula a coleta de métricas de redes sociais para análise de engajamento e tendências do mercado.

## 🚀 Tecnologias Utilizadas

  * **Linguagem de Programação:** Python
  * **OCR:** Tesseract OCR (via `pytesseract`)
  * **Automação de Interface:** `PyAutoGUI`
  * **Processamento de Imagens:** `Pillow`
  * **Integração com IA:** Google Gemini API (`google-generativeai`)
  * **Reconhecimento de Voz:** `SpeechRecognition`, `pydub`
  * **Banco de Dados Relacional:** PostgreSQL (`psycopg2-binary`) ou MySQL
  * **Gerenciamento de Ambiente:** `venv`
  * **Variáveis de Ambiente:** `python-dotenv`
  * **Controle de Versão:** Git
