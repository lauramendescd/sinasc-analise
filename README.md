# 🍼📊 Análise de Nascidos Vivos (SINASC - CE 2021)

Este projeto tem como objetivo realizar uma análise exploratória e visual sobre os dados de nascidos vivos no estado do Ceará, utilizando a base pública do **SINASC (Sistema de Informações sobre Nascidos Vivos)**, disponibilizada pelo **Datasus**.

---

## 📁 Estrutura do Projeto

├── data/

│   ├── raw/            ← dados brutos 

│   └── clean/          ← dados tratados 

├── notebooks/          ← notebooks separados por tema

│   ├── 01_importacao_dados.ipynb
│   ├── 02_limpeza_dados.ipynb
│   ├── 03_analise_exploratoria.ipynb
│   ├── 04_visualizacoes.ipynb

├── scripts/            ← trechos em Python

├── README.md           ← explicação do projeto

├── .gitignore

└── requirements.txt    ← bibliotecas usadas 

---

## 🧪 Etapas da Análise

1. **Importação dos dados**  
2. **Limpeza e pré-processamento**
3. **Análise descritiva e estatística**
4. ** Construção de um Modelo Preditivo**
5. **Visualização de padrões (gráficos e dashboards)**

---

## 🔧 Tecnologias Utilizadas

- Python (Pandas, Numpy)
- Visualizações com Seaborn e Matplotlib
- Google Colab
- Jupyter Notebook
- Git + GitHub

---

## 📊 Principais Insights

✅ Desenvolvemos um modelo preditivo para estimar o **risco de baixo peso ao nascer** com base em dados reais do SINASC (CE - 2021).  

✅ As variáveis de maior impacto no modelo foram:  
- **Número de consultas de pré-natal**  
- **Tipo de gravidez (única ou múltipla)**  
- **Semanas de gestação**  

✅ Aplicações práticas do modelo:  
- Auxílio a profissionais da saúde para monitoramento de gestantes em grupos de risco.  
- Suporte à formulação de políticas públicas focadas na redução de baixo peso ao nascer.  
- Promoção de campanhas educativas sobre a importância do pré-natal.  
- Melhoria do acesso a cuidados médicos em regiões vulneráveis.

---

## 🚀 Como Executar

   git clone https://github.com/lauramendescd/sinasc-analise.git
