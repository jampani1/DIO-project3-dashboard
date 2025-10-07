# Dashboard de Análise de Assinaturas em Excel - Desafio DIO

Olá! Seja bem-vindo(a) ao meu projeto de dashboard, desenvolvido como parte de um desafio prático do bootcamp da [Digital Innovation One (DIO)](https://www.dio.me/).

O objetivo foi transformar uma base de dados brutos relacionados à assinatura do Xbox em um painel interativo e funcional no Microsoft Excel, capaz de gerar insights e responder a perguntas de negócio essenciais.

## Sobre o Projeto

Este dashboard foi construído para analisar o desempenho de um serviço de assinaturas, focando em métricas de receita, aquisição de clientes, popularidade de produtos e retenção. O projeto abrange desde o tratamento inicial dos dados até a criação de um painel de controle interativo com filtros dinâmicos.

### 🛠️ Ferramentas e Técnicas Utilizadas

* **Microsoft Excel**: Plataforma principal para a construção do dashboard.
* **Tabelas Dinâmicas (PivotTables)**: Utilizadas para agregar, sumarizar e analisar os dados de forma eficiente.
* **Gráficos Dinâmicos (PivotCharts)**: Para a visualização dos dados e criação dos elementos do painel.
* **Segmentação de Dados (Slicers)**: Implementados para permitir a filtragem interativa de todo o dashboard, conectando múltiplos relatórios para uma análise sincronizada.
* **Fórmulas e Funções do Excel**: Uso de funções como `TEXTO` para tratamento de datas e `CONT.SE` para contagens específicas, além da criação de colunas auxiliares para corrigir a ordenação cronológica.

## 📊 Perguntas de Negócio Norteadoras

O desenvolvimento do dashboard foi guiado pelas seguintes perguntas estratégicas, focadas em diferentes áreas de análise do negócio:

#### 1. Desempenho Geral e Receita
* **Pergunta:** Como a aquisição de novos assinantes e a receita evoluíram ao longo do tempo (mês a mês)?
* **Importância:** Identificar tendências de crescimento, sazonalidade ou o impacto de campanhas de marketing.
* **Visualização:** Gráfico de linhas para a receita e gráfico de barras para o número de novos assinantes.

#### 2. Comportamento e Segmentação de Clientes
* **Pergunta:** Qual é a distribuição de clientes por tipo de assinatura (Mensal, Trimestral, Anual)?
* **Importância:** Entender o nível de comprometimento dos clientes, visto que planos anuais garantem receita a longo prazo.
* **Visualização:** Gráfico de pizza (ou rosca) para mostrar a distribuição percentual.

#### 3. Análise de Produtos e Serviços Adicionais
* **Pergunta:** Quais são os add-ons (EA Play, Minecraft) mais populares entre os assinantes?
* **Importância:** Mostrar quais produtos adicionais estão agregando mais valor e gerando mais interesse.
* **Visualização:** Gráfico de barras simples para comparar a contagem de assinantes de cada add-on.

#### 4. Retenção e Churn (Cancelamento)
* **Pergunta:** Clientes com planos mais longos (Anual) tendem a manter a renovação automática mais ativa do que clientes de planos mensais?
* **Importância:** Entender se o comprometimento inicial do cliente se traduz em maior lealdade e retenção a longo prazo.
* **Visualização:** Gráfico de barras agrupadas, mostrando a contagem de "Sim" e "Não" para a renovação automática dentro de cada tipo de plano.

## 🚀 Como Utilizar

Para explorar o dashboard, basta abrir o arquivo Excel e utilizar as **Segmentações de Dados** (filtros) disponíveis. Ao selecionar um mês, ano ou tipo de plano, todos os gráficos e indicadores do painel serão atualizados automaticamente, permitindo uma análise dinâmica e aprofundada.