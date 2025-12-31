# 🎮 Video Game Sales: Strategic Intelligence Analysis
> Uma análise de dados orientada a negócios, explorando o ciclo de vida da indústria de games.

![Evolução de Vendas de Video Games](img/vendas_animacao.gif)

Este projeto realiza uma análise exploratória de dados (EDA) sobre vendas globais de videogames, com foco em extração de insights orientados a negócio, análise de eficiência histórica por plataforma e diferenças regionais de mercado (América do Norte, Europa e Japão).

O trabalho foi desenvolvido como parte do meu processo de aprimoramento técnico em análise de dados, combinando estatística descritiva, visualização avançada e interpretação estratégica dos resultados.

🎯 Objetivos do Projeto

Aplicar técnicas de análise exploratória de dados em um dataset real

Praticar tratamento, padronização e validação de dados

Desenvolver visualizações analíticas e interativas

Traduzir padrões estatísticos em insights orientados a negócios

Simular um cenário de análise apresentado a gestores e stakeholders

## 🎯 Motivação e Valor de Negócio
Este projeto vai além da análise descritiva; ele simula uma consultoria de **Market Intelligence**. O objetivo foi identificar padrões de sucesso e barreiras de entrada no mercado global de games, fornecendo subsídios para tomadas de decisão sobre alocação de recursos em diferentes plataformas e regiões.

## 🛠️ Stack Técnica e Justificativa
* **Python (Pandas & NumPy):** Manipulação eficiente de grandes volumes de dados e tratamento de missing values.
* **Plotly Express:** Utilizado para criar visualizações dinâmicas e **animações temporais**, permitindo observar a transição de dominância entre consoles ao longo das décadas.
* **Seaborn & Matplotlib:** Empregados em análises estatísticas rigorosas (distribuição, boxplots de outliers) pela precisão acadêmica e estética limpa.
* **KaggleHub:** Integração via API para garantir a reprodutibilidade direta da fonte de dados mais atualizada.

---

## 📈 Pontos Chave da Análise (Business Insights)

### 1. Dinâmica Temporal e Animação de Vendas
O gráfico animado no topo do projeto revela o "boom" da sétima geração de consoles. 
* **Skill demonstrada:** Manipulação de eixos temporais e criação de visualizações interativas que facilitam a compreensão de tendências de longo prazo por stakeholders não técnicos.

### 2. Eficiência de Plataforma (Market Intelligence)
Identificamos que plataformas com alto volume de vendas (ex: DS, PC) possuem uma **fragmentação de receita** maior. Plataformas da Sony (PS2/PS3) demonstraram uma eficiência por título superior, indicando um ecossistema mais saudável para grandes lançamentos (AAA).
* **Skill demonstrada:** Cálculo de KPIs personalizados (Revenue per Title) e análise de market share.

### 3. Concentração de Sucesso (Cauda Longa)
Utilizando análises de quartis e dispersão, o projeto destaca a natureza "Winner-Takes-All" da indústria, onde uma pequena elite de títulos detém a vasta maioria do lucro global.

---

## 🧪 Estrutura do Repositório
* `notebooks/`: Versões [PT-BR] e [EN-US] detalhadamente comentadas.
* `img/`: Assets visuais e gráficos exportados para apresentações.
* `environment.yml`: Configuração completa do ambiente Conda para execução imediata (Zero Setup Error).

---

## 🚀 Como Visualizar
Para experimentar a interatividade total (filtros e animações):
1. Acesse o notebook via [NBViewer](link-aqui) ou [Google Colab](link-aqui).
2. Ou rode localmente seguindo as instruções de `environment.yml`.