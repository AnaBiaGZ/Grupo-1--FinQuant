# Grupo 1 - FinQuant

## Semana 1 - Reunião no dia 16/11/2025:

**Tópicos:**
- Revisão rápida das diretrizes do case 
- Definição do tema: Comparador de Estratégias de Alocação de Portfólio
- Definição do formato: projeto aplicado + aulão
- Tarefas iniciais: criação do repositório, incluindo README e este CHANGELOG
- Próximos passos: antes de iniciar a construção do projeto, vamos consolidar nossa base de conhecimento. Cada integrante continuará estudando os conteúdos até o começo do Módulo 4 (Backtesting de Estratégias). A partir desse ponto, marcaremos uma nova reunião e daremos início à parte prática do projeto. Além disso, vamos pesquisar materiais externos confiáveis para fortalecer nossa base teórica e garantir que o desenvolvimento do projeto seja bem embasado.

## Semana 2

Nesta semana, o grupo não realizou reunião. Mantivemos o foco na continuidade dos estudos individuais, dando sequência aos conteúdos necessários para consolidar nossa base teórica antes de iniciarmos a parte prática do projeto.

## Semana 6 - Reunião no dia 15/12/2025:

Até então não havíamos relizado nenhmuma reunião, pois tínhamos decidido estudar os módulos disponíveis antes de colocar o projeto em prática. Passados os estudos, marcamos uma nova reunião no dia 15/12 para um alinhamento prático do nosso trabalho. O objetivo foi definir a divisão técnica do projeto (sujeita a alterações se necessário), contendo:

    1- Configurações iniciais, sendo elas: montar a carteira (definir ativos), adicionar um benchmark, definir data de corte e definir taxa livre de risco;
    2- Tratamento de dados: limpeza, cálculo dos retornos diários, média e matriz de covariância dos retornos;
    3- Válidação estatística: aplicação de testes de estacionariedade (ADF) e autocorrelação (ACF) para validar a série temporal (baseado no Módulo 3);
    4- Modelagem (Markowitz): implementação das estratégias de alocação --> 1/N, Mínima Variância e Máximo Sharpe (sujeita a alterações);
    5- Simulação (Backtest): aplicação dos pesos históricos e cálculo da evolução patrimonial;
    6- Análise de risco e visualização: geração de gráficos comparativos e cálculo de drawdown;
    7- Resumo final: conclusão apresentando resultados

Vamos começar pesquisando os ativos com quais vamos trabalhar, focando em áreas específicas, como utilidade pública (energia/água), setor bancário, commodities, moda, entre outros. A ideia inicial é escolher um setor principal para focar o nosso estudo de caso e selecionar as melhores empresas dentro dele.

## Semana 7 - Reunião no dia 22/12/2025:

Nesta reunião, discutimos a definição dos ativos que serão utilizados no projeto. Nesse contexto, nosso mentor, Gabriel Navarro, recomendou a seleção de ativos pertencentes ao S&P 100, uma vez que o mercado estadunidense oferece maior disponibilidade, padronização e confiabilidade de dados históricos, o que facilita tanto a coleta quanto a manipulação das informações ao longo das análises.
Além disso, foi sugerido que o cálculo tradicional do Máximo Sharpe fosse adaptado, visando a adicionar criatividade no projeto. A proposta é ir além da otimização clássica média-variância e testar variações que possam gerar insights mais ricos e resultados potencialmente mais robustos. 
Por fim, o mentor também recomendou que a análise de risco das estratégias fosse apresentada após a discussão dos resultados de performance. Essa abordagem permite uma compreensão mais clara do perfil da estratégia e facilita sua classificação quanto ao público-alvo (conservador, moderado ou arrojado), reforçando a coerência entre retorno esperado e nível de risco assumido.