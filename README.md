# Análise de Séries Temporais usando Python 
Tradução do material do Workshop ["Time Series Analysis in Python"](https://github.com/rouseguy/TimeSeriesAnalysiswithPython)
de [Amit Kapoor](http://twitter.com/amitkaps) e [Bargava Subramanian](http://twitter.com/bargava)

**Nível de Experiência** : Iniciante

**Visão Geral**: Vários dados que nós vemos na natureza estão em séries temporais contínuas. Esse workshop dará uma visão geral em como analisar séries temporais e uma introdução a previsão de séries temporais.

**Público**: Pessoas interessadas em análise de dados em séries temporais.

**Objetivo**: 

1. O que é série temporal? 
2. Como visualizar séries temporais
3. Como analisar séries temporais? 
4. Como prever séries temporais?  


Dados meteorológicos, preços de ações, população de um pais são exemplos de séries temporais. Os dados são continuamente gravados diariamente, semanalmente, mensalmente,, etc. Embora muita teoria já tenha sido desenvolvida para representar e analisar séries temporais, muitas delas não funcionam bem com dados contínuos de séries temporais.

O objetivo desse workshop é duplo:

1. Como analisar/visualizar dados de séries temporais
2. Como fazer previsões usando os dados de séries temporais disponíveis

Adotaremos uma abordagem científica baseada em princípios sobre como coletar, preparar e explorá dados. Criaremos algumas métricas de resumo usando os dados disponíveis.

Em seguida definiremos o(s) problema(s) que queremos prever e introduziremos alguns dos mais comuns modelos de previsão de séries temporais os implementaremos usando Python.

**Esboço**

* Obtendo dados de séries temporais
* Determinar quais perguntas precisam ser respondidas
* Gerar hipoteses para várias abordagens de solução
* Explorando dados de séries temporais
  * Outliers
  * Valores faltantes (Missing values)
  * Criando métricas agregadas
  * Calcular o percentual/proporção das métricas
  * Métricas de resumo
* Visualizar dados de séries temporais
* Previsão de séries temporais
  * Regressão linear
  * Média móvel
  * Decomposição de séries temporais
  * ARIMA (média móvel integrada autorregressiva)
  * Modelos de Regressão Dinâmica
  * ARV (Auto-Regressão Vetorial)
  * Suavização Exponencial (Exponential Smoothing)



*Script para verificar se todas as dependências para o workshop está presente*

Por favor execute o seguinte comando no prompt de comando:

```sh
$ python check_env.py
```
Se alguma da biblioteca tiver a mensagem `FAIL`, por favor instale/atualize a referida biblioteca.

As instruções para instalação podem ser encontradas [aqui](https://github.com/rouseguy/TimeSeriesAnalysiswithPython/blob/master/installation_instructions.md)

---
### Licensing

Time Series Analysis using Python by <a href="https://twitter.com/amitkaps/">Amit Kapoor</a> and <a href="https://twitter.com/bargava/">Bargava Subramanian</a> is licensed under a <a rel="license" href="https://opensource.org/licenses/MIT">MIT License</a>.
