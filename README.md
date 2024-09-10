# Avaliação de Pescoço Grosso - Análise de Dados do WhatsApp

Este repositório contém a resolução da avaliação prática sobre análise de dados do WhatsApp utilizando Python, PostgreSQL e ferramentas de análise estatística e visualização de dados. Esta solução demonstra habilidades técnicas em banco de dados, manipulação de dados, análise estatística, visualização e machine learning, sendo uma excelente demonstração para recrutadores e profissionais da área.

## Estrutura do Repositório

- `analisys.ipynb`: Jupyter Notebook com todo o código da análise solicitada na avaliação.

## Objetivos da Análise

### 1. **Manipulação de Banco de Dados**
   - Restaurar o arquivo dump `fd_whatsapp_0911_2023.dump` no PostgreSQL.
   - Remover trava-zaps.
   - Eliminar duplicatas e textos com menos de 5 palavras.

### 2. **Análise Estatística**
   - **Para Atributos Numéricos**: 
     - Medidas de tendência central, variabilidade, tabelas de frequência, histogramas, boxplots, QQ-plots e teste de normalidade.
     - Melhor distribuição ajustada (best fit distribution).
   - **Para Pares de Atributos Numéricos**:
     - Coeficientes de correlação e gráficos de dispersão.
   - **Para Pares de Atributos Categóricos**:
     - Método V de Cramer para análise de correlação.

### 3. **Visualização de Dados**
   Foram criadas diversas visualizações para apresentar a relação entre diferentes métricas, incluindo:
   - Quantidades de grupos, usuários e mensagens.
   - Quantidade de mensagens de texto vs. com mídia.
   - Análise de tipos de mídia e estado/country.
   - Visualizações detalhadas de URLs, usuários ativos, domínios mais compartilhados e muito mais.
   - Nuvem de palavras e análise de sentimentos (mensagens positivas/negativas).
   - Proporções de desinformação e mensagens virais.

## Tecnologias Utilizadas

- **Python**: Para manipulação e análise dos dados (pandas, numpy, scipy).
- **PostgreSQL**: Banco de dados relacional para restaurar e manipular o dump.
- **Seaborn/Matplotlib**: Para visualização de dados.
- **Scikit-learn**: Para testes de normalidade e análises de correlação.
- **Statmodels**: Para ajustes de distribuição.
- **NLTK**: Processamento de linguagem natural (nuvem de palavras e trigramas).
- **Jupyter Notebook**: Para estruturação e execução do código.

## Resultados Importantes

- Identificação de mensagens mais compartilhadas e URLs mais frequentes.
- Análise dos sentimentos predominantes em diferentes regiões.
- Insights detalhados sobre padrões de compartilhamento de mídia vs. texto.
- Distribuições detalhadas por dia, hora, estado e país.
- Correlação entre mensagens e variáveis como número de palavras e desinformação.

## Como Executar

### Pré-requisitos:
- Python 3.x
- PostgreSQL (com a instalação do dump)
- Instalar dependências: `pip install -r requirements.txt`

### Passos:
1. Clone o repositório.
   ```bash
   git clone https://github.com/seu-usuario/avaliacao-pescoco-grosso.git
   ```
2. Restaure o dump no PostgreSQL.
   ```bash
   pg_restore -U usuario -d database data/fd_whatsapp_0911_2023.dump
   ```
3. Abra o Jupyter Notebook.
   ```bash
   jupyter notebook analisys.ipynb
   ```

## Contato

Para mais informações ou dúvidas entre em contato.
