# Power BI: Menus Interativos e Filtros Dinâmicos 🎨

Link do Dashboard: [Power BI](?)

Este projeto demonstra a criação de uma interface de usuário avançada no Power BI, focando na navegabilidade através de Indicadores (Bookmarks) e na visualização de filtros aplicados via Concatenação.

![GitHub Logo](/rendimiento-graficos-powerbi.jpg)

### Objetivos de Aprendizado 🎯

Menus Interativos: Uso de indicadores e botões para alternar entre diferentes visualizações ou expandir/recolher menus laterais sem mudar de página.

Contexto de Filtro: Implementação de medidas DAX para capturar e exibir de forma textual quais filtros estão selecionados pelo usuário.

User Experience (UX): Melhorar a fluidez do relatório, escondendo elementos complexos e exibindo-os apenas sob demanda.

### 🚀 Objetivos Técnicos

Desmonstrar o uso das funções:


### 🛠️ Recursos Utilizados

Indicadores (Bookmarks): Para salvar estados específicos do relatório (filtros, visibilidade de objetos e foco).

Painel de Seleção: Gerenciamento da visibilidade de camadas para criar o efeito de menu "pop-out".

DAX para Títulos Dinâmicos: ```dax Filtro Selecionado = "Exibindo dados de: " & SELECTEDVALUE(Tabela[Coluna], "Todos")

Botões com Ações: Gatilhos configurados para ativar os indicadores de "Abrir Menu" e "Fechar Menu".

### 📊 O que o projeto mostra
Como economizar espaço em tela usando menus retráteis.

Como dar feedback visual imediato ao usuário sobre a segmentação de dados ativa.