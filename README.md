
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Automate](https://img.shields.io/badge/Power_Automate-3A96DD?style=for-the-badge&logo=power-automate&logoColor=white)
![Microsoft Lists](https://img.shields.io/badge/Microsoft_Lists-57A4FF?style=for-the-badge&logo=microsoft-lists&logoColor=white)
![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?style=for-the-badge&logo=microsoft-sharepoint&logoColor=white)

💡 Projeto Área Colaborativa: Gestão de Inovação & Melhoria Contínua

📌 Visão Geral

Este projeto nasceu da necessidade de centralizar, gerenciar e metrificar as ideias de melhoria propostas pelos colaboradores. Foi criada uma plataforma de Inovação Aberta Interna integrada ao ecossistema Microsoft 365, onde sugestões são capturadas, votadas, priorizadas e implementadas com total transparência.

🎯 O Problema

Boas ideias se perdiam em e-mails ou conversas informais.
Falta de feedback para quem sugeria melhorias, gerando desengajamento.
Dificuldade em medir o impacto da inovação na empresa.

🛠️ A Solução: Gamificação e Gestão Visual

1. Coleta e Engajamento (Microsoft Lists)
Interface amigável para cadastro de sugestões.
Sistema de "Votos" (Likes) para que a própria equipe priorize as ideias mais relevantes.

2. Inteligência e Gestão (Power BI)
O dashboard atua como o "Placar do Jogo", monitorando todo o ciclo de vida de uma ideia, do brainstorming à implementação.

Métricas DAX Desenvolvidas:

Funil de Inovação: Monitoramento do status das ideias (Sugestões no Backlog -> Em Análise -> Em Andamento -> Implementadas).
KPIs de Engajamento: Total de Sugestões por área e Média de Votos por Sugestão para identificar temas de alto interesse.
SLA de Inovação: Medição precisa do tempo que a empresa leva para transformar uma ideia em realidade:
Tempo no Backlog: Espera para análise.
Tempo em Análise: Avaliação de viabilidade.
Tempo de Implementação: Execução técnica.
Jornada da Implementação (Lead Time): Tempo total ponta a ponta.

3. Engenharia de Dados
Tratamento de dados do SharePoint para normalizar datas e status.
Lógica COALESCE no DAX para garantir que métricas de tempo não quebrem quando há etapas vazias ou em andamento.

🚀 Resultados e Impacto
Cultura de Inovação: A visibilidade do painel (quem sugeriu, quem curtiu) estimulou a competição saudável e o envio de novas ideias.
Transparência: Colaboradores conseguem ver exatamente em que etapa está sua sugestão, eliminando a frustração da "caixa de sugestões esquecida".
Melhoria de Processos: As sugestões implementadas (monitoradas pelo painel) resultaram em otimizações diretas nos fluxos de trabalho da empresa.
