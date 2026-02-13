# SysInfra - Sistema de Dimensionamento e Quantificação de Fundações Profundas

![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow) ![Language](https://img.shields.io/badge/Language-Python-blue) ![Context](https://img.shields.io/badge/Context-Engenharia_Civil_ITA-green)

**SysInfra** é uma ferramenta computacional desenvolvida para automatizar a quantificação de armaduras (aço) em estacas de fundação. O projeto foi concebido no contexto de um estágio em Engenharia Civil no **ITA (Instituto Tecnológico de Aeronáutica)**, visando aumentar a produtividade, a rastreabilidade e a padronização no levantamento de quantitativos de obras de infraestrutura.

## 📋 Sobre o Projeto

O objetivo principal do software é converter parâmetros de projeto e detalhamento técnico em quantitativos consolidados de massa de aço (kg). A ferramenta atende à necessidade de calcular rapidamente o consumo de aço para diferentes cenários de fundações (como estacas hélice contínua e escavadas), gerando relatórios para orçamentação e planejamento conforme as normas brasileiras.

## 🚀 Funcionalidades Principais

### 1. Parametrização de Geometria e Armadura
O sistema permite a entrada intuitiva de dados através de uma interface gráfica amigável:
* **Geometria da Estaca:** Definição de diâmetro, comprimento do fuste e cobrimento.
* **Definição de Trecho Armado:** Flexibilidade para definir se a estaca é armada integralmente ou apenas nos metros iniciais (comum em estacas Hélice Contínua).

### 2. Detalhamento em Níveis (N1, N2, N3)
O software estrutura o cálculo da armadura em três níveis hierárquicos:
* **N1 - Armadura Longitudinal:** Quantidade e bitola das barras principais.
* **N2 - Armadura Transversal:** Suporte para estribos anelares (por espaçamento) ou armadura helicoidal (por passo).
* **N3 - Armadura de Enrijecimento:** Inclusão de anéis enrijecedores padronizados para gaiolas de armadura.

### 3. Base de Conhecimento Normativa
Integração com tabelas de recomendação baseadas na **ABNT NBR 6122**, oferecendo:
* Tabelas de dimensionamento padrão para Estacas Hélice Contínua e Escavadas.
* Sugestões de bitolas e espaçamentos mínimos conforme o diâmetro da estaca.

### 4. Relatórios e Exportação
* **Dashboard em Tempo Real:** Visualização imediata do peso total por estaca e total da obra.
* **Exportação:** Geração de relatórios técnicos em formato `.TXT` contendo o memorial de cálculo e o resumo de materiais.
* **Resumo de Materiais:** Consolidação por diâmetro (bitola) para facilitar a compra de insumos.

## 📸 Capturas de Tela

| Interface Principal | Tabelas Normativas |
|:-------------------:|:------------------:|
| *Preenchimento de parâmetros e cálculo* | *Consulta de padrões de norma* |
| ![Interface Principal](assets/interfaceprincipal.png) | ![Tabelas](assets/tabelarecomendada1.png) |


## 📚 Normas de Referência

O desenvolvimento do algoritmo de cálculo e as tabelas de recomendação baseiam-se nas seguintes normas técnicas:

* **ABNT NBR 6122:** Projeto e execução de fundações.
* **ABNT NBR 6118:** Projeto de estruturas de concreto - Procedimento.
* **ABNT NBR 7480:** Aço destinado a armaduras para estruturas de concreto armado.

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Interface Gráfica:** Tkinter / CustomTkinter (Desktop)
* **Cálculo:** Algoritmos de conversão de geometria linear para massa (kg) baseados em densidade linear nominal.

---
*Este projeto foi desenvolvido como parte das atividades de estágio curricular do curso de Engenharia Civil do ITA - Ano 2026.*
