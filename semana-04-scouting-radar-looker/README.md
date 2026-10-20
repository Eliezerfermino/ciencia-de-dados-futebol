# 📊 Dossiê Executivo de Recrutamento & Scouting Sub-23

Projeto prático desenvolvido para integrar análise de dados de mercado (Python) e visualização executiva interativa (Google Looker Studio), simulando a tomada de decisão para reforços de equipas técnicas profissionais.

---

## 🎯 Objetivo da Análise
Identificar e comparar o rendimento ofensivo de atletas sub-23 com recurso a métricas normalizadas por 90 minutos ($p90$), combinando:
1. **Visão Macro de Mercado:** Distribuição de volume ofensivo e minutos jogados.
2. **Visão Micro Tática:** Perfil individual em percentis face aos pares da liga (Caso de Estudo: *Lamine Yamal*).

---

## 🖼️ Perfil Tático Individual (Radar PyPizza)
Métricas calculadas em percentis (0 a 100) utilizando a biblioteca `mplsoccer`:

![Radar Lamine Yamal](radar_scouting.png)

> **Parecer Tático:** Extremo de desequilíbrio puro com dominância no 1x1 (Percentil 94 em dribles p90) e capacidade de passe de rutura (Percentil 91 em assistências p90).

---

## 💻 Painel Interativo no Looker Studio
O painel foi desenhado sob metodologia executiva com filtros dinâmicos de posição, idade e barras de dados:

- 🔗 **Link de Acesso ao Painel Interativo:** [Cole aqui o link de partilha do teu Looker Studio]

---

## 🛠️ Tecnologias e Ferramentas
- **Python / Pandas:** Limpeza, tratamento e cálculo de métricas normalizadas ($p90$).
- **Matplotlib & mplsoccer:** Construção e parametrização do gráfico de radar multidimensional (`PyPizza`).
- **Google Looker Studio:** Dashboard interativo com filtros de mercado e cartões de controlo (*Scorecards*).
