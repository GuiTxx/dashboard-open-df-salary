# 📊 Dashboard Interativo de Salários em Dados

## Descrição do Projeto

O **Dash de Salários em Dados** é uma aplicação web interativa desenvolvida com **Streamlit** e **Plotly** que permite realizar análises detalhadas e exploratórias sobre os salários na área de dados. O projeto foi desenvolvido durante a **Imersão dados_PYTHON da Alura** e oferece uma visão abrangente dos padrões salariais, considerando diversos fatores como senioridade, tipo de contratação, tamanho da empresa e período temporal.

### Objetivo

Este dashboard foi criado com o objetivo de:
- 🎯 Visualizar e analisar tendências salariais na indústria de dados
- 📈 Identificar padrões de remuneração por cargo e senioridade
- 🔍 Comparar salários entre diferentes tipos de contratação e tamanhos de empresa
- 📊 Fornecer insights baseados em dados reais e atualizados
- 🎨 Ofertar uma interface interativa e amigável para exploração de dados

---

## 🚀 Funcionalidades Principais

### 1. **Filtros Interativos**
O dashboard conta com uma barra lateral completa de filtros que permitem personalizar a análise:
- **Filtro de Ano**: Selecione um ou múltiplos anos para análises temporais
- **Filtro de Senioridade**: Escolha entre diferentes níveis de experiência (Junior, Pleno, Sênior, etc.)
- **Filtro de Tipo de Contratação**: Analise dados por CLT, PJ, Freelancer e outras modalidades
- **Filtro de Tamanho da Empresa**: Compare salários em micro, pequenas, médias e grandes empresas

### 2. **Métricas Principais (KPIs)**
Exibe indicadores-chave que resumem os dados filtrados:
- 💰 **Salário Médio Anual (USD)**: Média dos salários do conjunto filtrado
- 📍 **Salário Máximo (USD)**: Maior salário registrado na categoria selecionada
- 📋 **Total de Registros**: Quantidade de entradas de dados analisadas
- 👔 **Cargo Mais Frequente**: Posição mais comum no dataset filtrado

### 3. **Visualizações Gráficas**
O dashboard apresenta múltiplos gráficos interativos desenvolvidos com Plotly:
- **Top 10 Cargos por Salário Médio**: Gráfico de barras horizontal mostrando as 10 posições melhor remuneradas
- Todos os gráficos são responsivos e permitem hover para mais detalhes

### 4. **Interface Responsiva**
- Layout otimizado para diferentes tamanhos de tela
- Componentes bem organizados em colunas e seções
- Navegação intuitiva e clara

---

## 🛠️ Tecnologias Utilizadas

### Dependências Principais:
- **[Streamlit](https://streamlit.io/)** (v1.44.1): Framework para criar aplicações web interativas em Python
- **[Pandas](https://pandas.pydata.org/)** (v2.2.3): Manipulação e análise de dados
- **[Plotly](https://plotly.com/)** (v5.24.1): Visualizações gráficas interativas e responsivas

### Linguagem:
- **Python 3.x**: Linguagem de programação principal

---

## 📦 Como Usar

### Pré-requisitos
- Python 3.8 ou superior instalado
- pip (gerenciador de pacotes Python)

### Instalação

1. **Clone ou baixe o repositório:**
```bash
git clone https://github.com/seu-usuario/dash_salarios.git
cd dash_salarios
```

2. **Crie um ambiente virtual (recomendado):**
```bash
python -m venv .venv
```

3. **Ative o ambiente virtual:**

**Windows:**
```bash
.venv\Scripts\activate
```

**macOS/Linux:**
```bash
source .venv/bin/activate
```

4. **Instale as dependências:**
```bash
pip install -r requirements.txt
```

### Executando a Aplicação

Com o ambiente virtual ativado, execute:

```bash
streamlit run app.py
```

A aplicação será aberta automaticamente no seu navegador padrão (geralmente em `http://localhost:8501`).

---

## 📊 Fonte de Dados

Os dados utilizados neste projeto são carregados dinamicamente de um repositório GitHub:

```
https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv
```

O dataset contém informações detalhadas sobre:
- Salários em USD
- Anos de referência
- Níveis de senioridade
- Tipos de contratação
- Tamanho das empresas
- Cargos/Posições

---

## 📁 Estrutura do Projeto

```
dash_salarios/
├── app.py                 # Arquivo principal da aplicação
├── requirements.txt       # Dependências do projeto
└── README.md             # Este arquivo
```

---

## 🎓 Contexto Educacional

Este projeto foi desenvolvido como parte da **Imersão dados_PYTHON da Alura**, uma jornada de aprendizado intensivo em análise de dados com Python proporcionada pela plataforma de educação tecnológica Alura. Durante este processo, foram aplicados conceitos de:

- Manipulação de dados com Pandas
- Criação de visualizações com Plotly
- Desenvolvimento de aplicações web com Streamlit
- Análise exploratória de dados (EDA)
- Criação de interfaces interativas e user-friendly

---

## 💡 Insights Possíveis

Com este dashboard, você pode obter insights sobre:
- Como o salário varia com a senioridade
- Diferenças salariais entre tipos de contratação (CLT vs PJ)
- Influência do tamanho da empresa na remuneração
- Evolução dos salários ao longo dos anos
- Cargos com melhor remuneração na área de dados

---

## 🤝 Conecte-se

Desenvolvido com dedicação e paixão por análise de dados!

👤 **Autor**: Gui TXX  
🔗 **LinkedIn**: [linkedin.com/in/guitxx](https://www.linkedin.com/in/guiteixeiracunha)

Fique à vontade para conectar, fazer sugestões ou discutir melhorias no projeto!

---

## 📝 Licença

Este projeto é fornecido "tal qual" para fins educacionais e de aprendizado.

---

## 🚀 Possíveis Melhorias Futuras

- [ ] Adicionar mais tipos de visualizações (gráficos de linha, scatter plots, heatmaps)
- [ ] Implementar análises de correlação entre variáveis
- [ ] Adicionar exportação de dados filtrados em CSV/Excel
- [ ] Criar comparativos ano a ano
- [ ] Implementar machine learning para previsão de salários
- [ ] Adicionar análise de distribuição salarial por região

---

## 📞 Suporte

Se tiver dúvidas ou encontrar problemas ao executar o projeto, fique à vontade para:
- Abrir uma issue no repositório
- Entrar em contato via LinkedIn
- Enviar um email com sua dúvida

---

**Último Update**: Fevereiro de 2026  
**Status**: ✅ Ativo e pronto para uso
