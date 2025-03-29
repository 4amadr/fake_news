# Análise de Notícias Falsas (Fake News)

Este projeto explora um dataset de notícias falsas para identificar padrões, temas recorrentes e outliers utilizando técnicas de processamento de linguagem natural (NLP) e machine learning.

## Objetivo
Analisar características de fake news, como:
- Palavras-chave mais frequentes em títulos e textos.
- Distribuição por assunto e variação temporal.
- Detecção de manchetes atípicas (outliers).

## Tecnologias Utilizadas
- **Python** (Pandas, NLTK, Scikit-learn)
- **Visualização**: Seaborn, Matplotlib
- **Pré-processamento**: Regex, TF-IDF
- **Machine Learning**: Isolation Forest para detecção de outliers

## Dataset
O dataset `fake.csv` contém:
- **Título**: Manchete da notícia.
- **Texto**: Conteúdo completo.
- **Assunto**: Categoria temática (ex: News, Politics).
- **Data**: Data de publicação.

## Principais Análises
1. **Frequência de Palavras**:
   - Títulos: "Trump", "Video", "Watch" são termos dominantes.
   - Textos: Discussões políticas com menos termos sensacionalistas que os títulos.

2. **Distribuição por Assunto**:
   - 90% das fake news concentram-se em "News" e "Politics".

3. **Variação Temporal**:
   - Picos em períodos eleitorais (2016-2017), correlacionados a eventos como investigações do FBI.

4. **Detecção de Outliers**:
   - 20% das manchetes foram classificadas como atípicas, muitas com acusações extremas (ex: "Racist Alabama Cops Brutalize Black Boy").

## Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/analise-fake-news.git
Instale as dependências:

bash
Copy
pip install pandas seaborn matplotlib scikit-learn nltk
Execute o Jupyter Notebook:

bash
Copy
jupyter notebook analise_noticias.ipynb
Resultados
Gráficos interativos: Visualização de tendências temporais e distribuição de temas.

Lista de outliers: Manchetes identificadas como atípicas para análise qualitativa.

Melhorias Futuras
Adicionar dataset de notícias verdadeiras para comparação.

Implementar modelos de classificação (ex: SVM, Redes Neurais) para automação de detecção.

Contribuições
Sugestões e pull requests são bem-vindos! Vamos combater a desinformação com dados! 📊🔍

Copy

---

### Destaques para Recrutadores:
- **Habilidades Técnicas**: Manipulação de dados (Pandas), NLP, visualização, machine learning.
- **Aplicação Prática**: Foco em problemas reais (combate a fake news).
- **Clareza e Profissionalismo**: Estrutura replicável e documentação detalhada. 

Esses materiais destacam sua capacidade de transformar dados em insights acionáveis, um diferencial para oportunidades em análise de dados e ciência de dados! 🌟
