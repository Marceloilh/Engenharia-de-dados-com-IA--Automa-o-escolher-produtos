🚀 Plataforma de Automação e Análise de Vendas para Afiliados com IA e Voz 🚀

Descrição do Projeto
Este projeto é uma plataforma inovadora desenvolvida em Python, focada em otimizar e automatizar processos de vendas para afiliados, 
utilizando Inteligência Artificial e processamento de voz. O objetivo principal é transformar dados brutos (da tela, voz e APIs) em informações acionáveis e conhecimento, 
aprimorando a tomada de decisão e a eficiência operacional no nicho de marketing de afiliados.

O projeto foi concebido para demonstrar proficiência em diversas áreas da Engenharia de Dados, incluindo:

Desenvolvimento e manutenção de pipelines de dados.

Modelagem de Banco de Dados (relacional) para fins analíticos.

Execução de processos ETL.

Desenvolvimento de consultas SQL otimizadas.

Conhecimento em programação (Python).

Adesão a boas práticas de engenharia de software.

Funcionalidades Principais
Leitura e Resposta Inteligente:

Captura de texto da tela via OCR (Optical Character Recognition).

Processamento do texto capturado por um Large Language Model (LLM) para gerar respostas coerentes.

Automação da digitação de respostas na tela.

Comandos de Voz e Automação:

Reconhecimento de fala (Speech-to-Text) para interpretar comandos de voz.

Processamento por IA para extrair intenções e dados de pedidos.

Automação de ações e registros no banco de dados com base em comandos de voz.

Gestão de Produtos Afiliados:

Simulação de ingestão de dados de produtos de plataformas como Hotmart via API.

Recomendação de produtos para vendas utilizando IA, baseada em dados de mercado e do banco de dados.

Análise de Vendas e Métricas:

Armazenamento de dados de produtos, interações e pedidos em um banco de dados relacional (PostgreSQL/MySQL).

Consultas SQL para análise de desempenho de produtos e tendências de pedidos.

Simulação de coleta de métricas de redes sociais para análise de engajamento e tendências.

Arquitetura do Projeto

A arquitetura do projeto segue um fluxo de dados bem definido, abrangendo desde a ingestão de dados brutos até a geração de insights e automação.

Componentes Chave:

Fontes de Dados: Tela (via OCR), Microfone (via Speech-to-Text), APIs de Plataformas de Afiliados (Hotmart) e Redes Sociais.

Módulos de Ingestão e Pré-processamento: Responsáveis por coletar e preparar os dados.

LLM (Large Language Model): Utilizado para análise, recomendação e geração de respostas.

Módulos ETL: Processam os dados para carregamento no banco de dados relacional.

Banco de Dados Relacional: Armazenamento centralizado de dados estruturados.

Consultas SQL: Extração de informações para análise e relatórios.

Automação/Relatórios: Geração de ações automatizadas e apresentação de insights.

Tecnologias Utilizadas
Linguagem de Programação: Python

OCR: Tesseract OCR (pytesseract)

Automação de Interface: PyAutoGUI

Processamento de Imagens: Pillow

Integração com IA: Google Gemini API (google-generativeai)

Reconhecimento de Voz: SpeechRecognition, pydub

Banco de Dados Relacional: PostgreSQL (com psycopg2-binary) ou MySQL

Gerenciamento de Ambiente: venv

Variáveis de Ambiente: python-dotenv

Controle de Versão: Git
