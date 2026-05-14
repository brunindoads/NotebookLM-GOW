# 🪓 Miniguia de Estudos: O Universo de God of War (NotebookLM)

Este repositório foi desenvolvido como parte de um desafio de projeto na **DIO (Digital Innovation One)**. O objetivo é demonstrar a utilização da Inteligência Artificial, especificamente o **NotebookLM**, como uma ferramenta de aprendizagem ativa para curadoria e organização de conhecimento técnico sobre games.

## 🎯 Contexto e Objetivos
O tema escolhido para este caderno temático é a franquia **God of War**, com foco no *God of War Collection*. O objetivo é transformar guias brutos e informações esparsas em um material de estudo estruturado para jogadores que buscam maestria no combate e na exploração.

**Objetivos específicos:**
* Sintetizar mecânicas de combate e estratégias de progressão.
* Mapear a localização de itens colecionáveis essenciais.
* Documentar o processo de interação com a IA para extração de dados precisos.

## 📚 Curadoria de Fontes
Para alimentar o NotebookLM, foram selecionadas as seguintes fontes (disponíveis no portal Guia do ED):
1.  **Guia de Controles e Movimentação:** Instruções minuciosas sobre os comandos básicos e avançados.
2.  **Roteiro de Combate e Estratégia:** Táticas para enfrentar inimigos e chefes fundamentais.
3.  **Manual de Resolução de Puzzles:** Passo a passo para os quebra-cabeças que travam o progresso.
4.  **Mapa de Colecionáveis:** Localização exata de Olhos de Gorgon e Penas de Fênix.

## 🧠 Engenharia de Prompts e "Cicatrizes"
O maior desafio foi filtrar informações irrelevantes (como notícias de outros jogos citadas na fonte) para focar apenas no guia técnico. Abaixo, registro o raciocínio aplicado:

| Pergunta/Prompt Estratégico | Resposta Obtida | "Cicatriz" e Troubleshooting |
| :--- | :--- | :--- |
| "Quais são os itens mais importantes do jogo?" | A IA listou itens de cura e armas. | **Ajuste:** O prompt precisou ser mais específico para focar em *estatísticas permanentes* (HP/MP). |
| "Extraia o passo a passo para coletar Olhos de Gorgon." | Gerou um resumo muito longo e confuso. | **Ajuste:** Pedi para "estruturar em formato de checklist numerado por região". |
| "Resuma o mercado de games citado." | Misturou God of War com Forza e Subnautica. | **Ajuste:** Usei o filtro de fonte do NotebookLM para focar apenas nos documentos de guia. |

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
O conteúdo consolida a jornada de Kratos como um equilíbrio entre força bruta e inteligência. A progressão não depende apenas de derrotar inimigos, mas da exploração meticulosa do cenário para encontrar baús ocultos que expandem as barras de vida e magia através dos Olhos de Gorgon e Penas de Fênix.

### 2. Glossário de Conceitos
* **Olhos de Gorgon:** Itens que, ao serem acumulados em conjuntos, aumentam permanentemente a barra de Saúde (HP).
* **Penas de Fênix:** Itens que aumentam a barra de Magia (MP), permitindo o uso frequente de habilidades especiais.
* **Quick Time Events (QTE):** Mecânica de combate que exige pressionar botões em sequência para finalizar inimigos.
* **Puzzles Ambientais:** Desafios que utilizam elementos do cenário (alavancas, estátuas) para desbloquear caminhos.

### 3. Prompts Reutilizáveis para Revisão
* *"Liste todos os colecionáveis encontrados na fase [Nome da Fase] de acordo com as fontes."*
* *"Explique a estratégia recomendada para derrotar chefes usando apenas ataques de longa distância."*
* *"Quais quebra-cabeças dependem do uso do ambiente e como resolvê-los?"*

---
✨ **Projeto desenvolvido por brunindoads**
