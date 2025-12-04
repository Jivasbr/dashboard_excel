# 🎮 Projeto de Análise de Dados: Dashboard Xbox

## 📊 Visão Geral do Projeto

Este projeto utiliza uma planilha do Excel para criar um **Dashboard interativo** focado na análise de dados relacionados ao ecossistema Xbox (vendas, performance de jogos, assinaturas, ou métricas específicas).

O objetivo principal é fornecer uma visão rápida e visual das métricas de desempenho mais importantes, permitindo tomadas de decisão baseadas em dados.

------

## 🛠️ Estrutura da Planilha (`dash_xbox_finalizada.xlsx`)

A planilha está organizada em abas distintas para garantir a clareza e a manutenção dos dados e cálculos:

| **Aba**         | **Descrição**                                                | **Conteúdo Principal**                                       |
| --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **`Dashboard`** | **Painel de Visualização Principal.** Contém gráficos, indicadores (KPIs) e filtros interativos. | Visualizações (Gráficos, Segmentadores, Cartões de Indicadores). |
| **`Bases`**     | **Dados Brutos.** Contém as tabelas originais e limpas que servem como fonte de dados para todos os cálculos. | Tabelas de vendas, usuários, jogos, ou assinaturas.          |
| **`Cálculos`**  | **Fórmulas e Métricas Derivadas.** Esta aba armazena os cálculos complexos, tabelas dinâmicas ou métricas de apoio necessárias para o dashboard. | Cálculos de taxa de conversão, crescimento mensal, rankings, etc. |
| **`Assets`**    | **Recursos de Apoio.** Pode conter listas de validação, referências de cores, ou imagens/ícones usados no dashboard. | Listas fixas (ex: categorias de jogos), ou referências visuais. |

------

## 🔍 Como Utilizar o Dashboard

1. **Abrir o Arquivo:** Abra o arquivo `dash_xbox_finalizada.xlsx` no Microsoft Excel.
2. **Acessar o Painel:** Navegue para a aba **`Dashboard`**.
3. **Interagir:** Utilize os **filtros** (segmentadores de dados ou caixas de combinação) presentes no painel para:
   - Filtrar dados por **período** (mês, ano).
   - Filtrar por **jogo** ou **categoria**.
   - Filtrar por **região** (se aplicável).
4. **Atualizar Dados (Se Necessário):** Se as tabelas na aba `Bases` forem atualizadas com novos dados, certifique-se de **atualizar todas as Tabelas Dinâmicas** (clique direito em qualquer Tabela Dinâmica na aba `Cálculos` ou `Dashboard` e selecione **"Atualizar"**).