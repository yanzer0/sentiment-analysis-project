# 📊 Análise de Sentimentos - Plataformas de Streaming

## Sobre o Projeto
Análise de sentimentos dos usuários brasileiros sobre as principais plataformas de streaming (Netflix, Amazon Prime, Disney+) utilizando Python, processamento de linguagem natural e visualização de dados.

## 🎯 Objetivos
- Coletar e analisar comentários em redes sociais sobre serviços de streaming
- Identificar o sentimento geral dos usuários em relação a cada plataforma
- Descobrir os principais pontos positivos e negativos mencionados
- Gerar insights acionáveis através de visualizações

## 🛠️ Tecnologias Utilizadas
- Python 3.9
- PRAW (Reddit API)
- NLTK e TextBlob para processamento de linguagem natural
- Pandas para manipulação de dados
- Matplotlib e Seaborn para visualizações
- GitHub para versionamento de código

## 📊 Principais Descobertas

### Distribuição de Sentimentos
- 63.92% comentários neutros
- 26.65% comentários positivos
- 9.43% comentários negativos

### Análise por Plataforma

#### Disney+
- Maior média de sentimento positivo: 0.080
- Maior índice de subjetividade: 0.306
- Total de posts analisados: 2,451

#### Netflix
- Média de sentimento: 0.050
- Maior volume de comentários: 9,600 posts
- Índice de subjetividade: 0.262

#### Amazon Prime
- Média de sentimento: 0.072
- Índice de subjetividade: 0.270
- Total de posts analisados: 3,091

## 📈 Resultados e Insights

### Pontos Positivos
1. Todas as plataformas mantêm média de sentimento positiva
2. Alto volume de engajamento, especialmente na Netflix
3. Disney+ gera comentários mais emocionais/subjetivos

### Pontos de Atenção
1. Netflix tem a menor média de sentimento positivo
2. Disney+ tem menor volume de comentários
3. Aproximadamente 1 em cada 10 comentários é negativo

## 📂 Estrutura do Projeto

sentiment-analysis-project/
├── data/                   # Dados brutos e processados
├── docs/                  # Documentação
├── notebooks/             # Jupyter notebooks
│   └── 01_coleta_dados.ipynb
├── src/                   # Código fonte
├── tests/                  # Testes
└── README.md


## 🚀 Como Executar
sentiment-analysis-project/
├── 1. Clone o repositório
│   └── git clone https://github.com/yanzer0/sentiment-analysis-project.git
│
├── 2. Instale as dependências
│   └── pip install -r requirements.txt
│
├── 3. Configure as credenciais do Reddit no arquivo .env
│   ├── REDDIT_CLIENT_ID=seu_client_id
│   ├── REDDIT_CLIENT_SECRET=seu_client_secret
│   └── REDDIT_USER_AGENT=SentimentAnalysis/1.0
│
└── 4. Execute os notebooks na ordem numérica
└── jupyter notebook notebooks/01_coleta_dados.ipynb


## 📝 Autor
Yan Botossi Galasso

## 📜 Licença
Este projeto está sob a licença MIT.