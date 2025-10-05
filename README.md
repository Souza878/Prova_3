#  Visualização e Aceleração Computacional em Python

##  Estrutura do Projeto

### 🔹 Introdução
Apresenta uma breve contextualização sobre a importância das ferramentas **Matplotlib**, **Plotnine** e **Numba** para aplicações em ciência de dados e modelagem computacional.

### 🔹 Parte 1 — Plotagem em Python
Nesta seção, são apresentados exemplos de gráficos com as bibliotecas:
- **Matplotlib** – para visualizações clássicas e altamente customizáveis.
- **Plotnine** – baseada na gramática de gráficos do R (ggplot2), com foco em estilo e simplicidade.

São usados conjuntos de dados simples (gerados artificialmente ou obtidos do **Seaborn** / **Scikit-learn**), com **pelo menos dois gráficos em cada biblioteca**, destacando diferenças de sintaxe e estilo.

### 🔹 Parte 2 — Aceleração com Numba
Implementação do **método de Monte Carlo** para estimar o valor de π:
- Primeiramente em **Python puro**
- Em seguida com **Numba** para aceleração via compilação JIT (Just-In-Time)

Os tempos de execução são comparados e comentados, evidenciando os ganhos de desempenho.

### 🔹 Conclusão
Síntese dos resultados e discussão sobre a importância das ferramentas estudadas no contexto da **ciência de dados**.

---

## ⚙️ Requisitos

Antes de executar o `.qmd`, certifique-se de ter as bibliotecas necessárias instaladas:

```bash
pip install matplotlib seaborn plotnine numba scikit-learn pandas

