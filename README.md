# Sprint 6 – Projeto Ice: Análise de Dados de Videogames

## Descrição do Projeto

Este projeto integra todas as habilidades adquiridas até agora no curso de análise de dados. Você atua como analista para a loja online **Ice**, que vende videogames mundialmente. O objetivo é identificar padrões que determinam o sucesso de um jogo, auxiliando na previsão de vendas e planejamento de campanhas publicitárias.

O conjunto de dados fornecido contém informações históricas sobre vendas de jogos, avaliações de usuários e críticos, gêneros, plataformas e classificações ESRB, abrangendo dados até 2016.

---

## Objetivos

- Limpar e preparar os dados para análise.
- Explorar padrões de vendas por ano, plataforma e gênero.
- Determinar a influência das avaliações de usuários e críticos sobre vendas.
- Comparar plataformas e identificar tendências de mercado.
- Formular e testar hipóteses estatísticas.
- Construir gráficos e tabelas explicativas para insights claros.

---

## Descrição dos Dados

O dataset contém as seguintes colunas:

- `Name`: nome do jogo  
- `Platform`: plataforma (ex.: Xbox, PlayStation)  
- `Year_of_Release`: ano de lançamento  
- `Genre`: gênero do jogo  
- `NA_sales`: vendas na América do Norte (milhões USD)  
- `EU_sales`: vendas na Europa (milhões USD)  
- `JP_sales`: vendas no Japão (milhões USD)  
- `Other_sales`: vendas em outros países (milhões USD)  
- `Critic_Score`: pontuação da crítica (0-100)  
- `User_Score`: pontuação dos usuários (0-10)  
- `Rating`: classificação ESRB (ex.: Teen, Mature)  

> Observação: os dados de 2016 podem estar incompletos. Valores ausentes podem conter a abreviação TBD ("to be determined").

---

## Etapas do Projeto

1. **Abrir o arquivo de dados**  
   - `/datasets/games.csv`  
   - Estudar informações gerais do dataset.

2. **Preparar os dados**  
   - Renomear colunas para minúsculas.  
   - Ajustar tipos de dados.  
   - Tratar valores ausentes e casos TBD.  
   - Calcular vendas totais globais por jogo.

3. **Análise exploratória**  
   - Número de jogos lançados por ano.  
   - Distribuição de vendas por plataforma e evolução ao longo do tempo.  
   - Identificar plataformas populares e em declínio.  
   - Construir diagramas de caixa para vendas globais por plataforma.  
   - Avaliar impacto de pontuações de usuários e críticos nas vendas.  
   - Analisar distribuição de vendas por gênero.

4. **Perfil de usuário por região (NA, EU, JP)**  
   - Top 5 plataformas por região.  
   - Top 5 gêneros por região.  
   - Influência da classificação ESRB nas vendas regionais.

5. **Testes de hipóteses**  
   - Comparar pontuações médias de usuários entre plataformas Xbox One e PC.  
   - Comparar pontuações médias de usuários entre gêneros Action e Sports.  
   - Explicar hipóteses nula e alternativa, definir nível de significância e interpretar resultados.

6. **Conclusão geral**  
   - Resumir resultados e insights.  
   - Destacar recomendações estratégicas baseadas na análise.

---

## Critérios de Avaliação

Os revisores avaliarão:

- Clareza na identificação e descrição de problemas nos dados.  
- Preparação e limpeza do dataset.  
- Construção e interpretação de gráficos e tabelas.  
- Cálculo de média, variância e desvio padrão.  
- Formulação e teste de hipóteses.  
- Estruturação do projeto e organização do código.  
- Conclusões e insights apresentados.  
- Comentários explicativos a cada etapa.

---

