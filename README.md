SysInfra - Sistema de Dimensionamento e Quantificação de Fundações Profundas
SysInfra é uma ferramenta computacional desenvolvida para automatizar a quantificação de armaduras (aço) em estacas de fundação. O projeto foi concebido no contexto de um estágio em Engenharia Civil no ITA (Instituto Tecnológico de Aeronáutica), visando aumentar a produtividade e a padronização no levantamento de quantitativos de obras de infraestrutura.

📋 Sobre o Projeto
O objetivo principal do software é converter parâmetros de projeto e detalhamento técnico em quantitativos consolidados de massa de aço (kg), garantindo rastreabilidade e conformidade com normas técnicas brasileiras. A ferramenta atende à necessidade de calcular rapidamente o consumo de aço para diferentes cenários de fundações, gerando relatórios para orçamentação e planejamento.
+1

🚀 Funcionalidades Principais
1. Parametrização Completa da Estaca
O sistema permite a entrada de dados geométricos e de armação de forma intuitiva:

Geometria: Definição de diâmetro, comprimento total do fuste e cobrimento.


Comprimento Armado: Flexibilidade para definir se a estaca é armada integralmente (ex: Estaca Raiz) ou parcialmente (ex: Estaca Hélice Contínua, tipicamente armada nos metros iniciais).

2. Detalhamento de Armaduras (N1, N2, N3)
O software estrutura o cálculo da armadura em três níveis hierárquicos, conforme visualizado na interface:

N1 - Armadura Longitudinal: Quantidade e bitola das barras principais.


N2 - Armadura Transversal: Suporta tanto estribos anelares (definidos por espaçamento) quanto armadura helicoidal (definida por passo).

N3 - Armadura de Enrijecimento: Inclusão de estribos/anéis enrijecedores padronizados, comuns em gaiolas longas de estacas hélice.

3. Base de Conhecimento Normativa
O sistema possui uma aba de "Tabelas de Recomendação" integrada, que fornece ao engenheiro dados padronizados baseados na ABNT NBR 6122:2019:

Tabelas de dimensionamento padrão para Estacas Hélice Contínua e Escavadas.

Sugestões automáticas de bitolas e espaçamentos mínimos conforme o diâmetro da estaca.

4. Saídas e Relatórios
Dashboard em Tempo Real: Visualização imediata do peso total por estaca e total da obra na interface principal.

Exportação de Dados: Funcionalidade de exportar o relatório técnico e quantitativo em formato .TXT para integração com outros softwares ou planilhas.


Sumário de Materiais: Consolidação por diâmetro (bitola) para facilitar a compra de insumos.

🛠️ Tecnologias e Normas Utilizadas

Linguagem: Python (foco em engenharia e automação).

Interface Gráfica (GUI): Desenvolvida para ambiente Desktop (Windows), com formulários de entrada e grids de resultados.

Normas de Referência:

ABNT NBR 6122 (Projeto e execução de fundações).

ABNT NBR 6118 (Projeto de estruturas de concreto).

ABNT NBR 7480 (Aço destinado a armaduras).

⚙️ Fluxo de Uso
Entrada de Dados: O usuário seleciona o tipo de estaca (ex: Hélice Contínua), define o diâmetro e os comprimentos (fuste e armado).

Configuração da Armadura: Preenche-se a quantidade de barras longitudinais (N1), o tipo de estribo (N2) e eventuais enrijecedores (N3).


Processamento: O botão "Adicionar Estaca" insere o elemento na lista, e "Calcular Quantitativos" processa a massa total baseada no peso linear das bitolas.

Consulta e Exportação: O usuário pode consultar as tabelas normativas na própria ferramenta e, ao final, exportar o memorial de cálculo.
