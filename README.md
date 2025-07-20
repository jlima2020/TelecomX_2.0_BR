# 📊 TelecomX_2.0 - Análise de Evasão de Clientes

Este projeto tem como objetivo investigar os fatores que influenciam a evasão de clientes (churn) em uma operadora de telecomunicações, utilizando técnicas de análise exploratória, modelagem preditiva e visualizações estratégicas.

---

## 🎯 Objetivos

- Identificar as principais variáveis que afetam o churn.
- Explorar padrões entre categorias de serviço, contratos e perfil de clientes.
- Criar modelos preditivos para antecipar evasão.
- Propor estratégias de retenção com base nos resultados obtidos.

---

## 🛠️ Tecnologias e Ferramentas

- Python
- Pandas / NumPy
- Scikit-learn / Imbalanced-learn
- Matplotlib / Seaborn
- Jupyter Notebook


---

## 📂 Estrutura do Projeto


---

## 📈 Etapas Realizadas

1. **Coleta de dados** via JSON remoto hospedado no GitHub.
2. **Tratamento de variáveis categóricas** (One-Hot Encoding).
3. **Análise de desequilíbrio das classes** e aplicação de SMOTE.
4. **Modelos utilizados**:
   - Regressão Logística (com padronização)
   - Random Forest (sem padronização)
5. **Avaliação dos modelos**:
   - Acurácia, Precisão, Recall, F1-score, Matriz de confusão.
6. **Visualizações**:
   - Gráficos de barras, pizza, boxplots e dispersão para entender padrões de evasão.
7. **Análise de importância das variáveis** com base nos modelos.

---

## 🌟 Principais Descobertas

- Clientes com **contratos curtos** e **serviço de internet sem segurança online** apresentaram maior taxa de evasão.
- **Total gasto** e **tempo de contrato** mostraram forte correlação com churn.
- O modelo **Random Forest** teve o melhor desempenho com F1-score elevado.
- A classe minoritária (clientes evadidos) exigiu técnicas de balanceamento para evitar viés nos modelos.

---

## 💡 Estratégias Recomendadas

- Oferecer upgrades de contrato com benefícios.
- Ativar segurança online como diferencial competitivo.
- Monitorar perfis com baixo engajamento e suporte técnico desativado.
- Criar campanhas de retenção segmentadas com base nos insights.

---

## 📌 Como Reproduzir

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# Instalar dependências
pip install -r requirements.txt

# Abrir o notebook
jupyter notebook notebooks/analise_telecom.ipynb


