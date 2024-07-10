# Finance

### Taxa de Crescimento 
> Reflete o quanto estamos multiplicamos nosso capital sobre o valor da data de compra. Para calcularmos ela usaremos os valores dos ativos normalizados, ou seja, dividindo o preço de fechamento de cada dia, pelo preço inicial de compra.
 
### Taxa de Retorno Simples
> A taxa de retorno simples é uma métrica financeira utilizada para avaliar a rentabilidade de um investimento ao longo de um período de tempo específico, ela é utilizada quando se quer **comparar ações distintas**.

$RS = (pf + div) - pi/(pi) * 100$

- pf = Preço Final
- pi = Preço Inicial
- div = dividendos do período 

#### Exemplo: 

TOTS3
- pi = R$ 27,93
- qi = 100 (quantidade de compra)
- pf = R$ 35,73
- qf = 100 (quantidade de venda)
- div = 0,25 
- Corretagem = 10,0

> $100 * 27,93 = 2.793$ 
> 
> $100 * 35,73 = 3.573$
> 
> $100 * 0,25 = 25,00$
> 
> $Lucro = (3.573 + 25,00) - 2.793 - 10,0 = 795,00$
> 
> $RS = (3.573 + 25 - 10) - (2.793 + 10)/(2.793 + 10) * 100$ -> 28,0% 

### Taxa de Retorno Logaritmica
> Também conhecida como taxa de retorno contínuo. Assim como a taxa de retorno simples, ela avalia a rentabilidade de um investimento ao longo de um período de tempo específico, sendo utilizada quando se quer **comparar a mesma ações em períodos diferentes**.

$RL = log⁡(pf/pi)* 100$

- pf = Preço Final
- pi = Preço Inicial
- div = dividendos do período 

#### Exemplo: 

TOTS3
- pi = R$ 27,93
- qi = 100 (quantidade de compra)
- pf = R$ 35,73
- qf = 100 (quantidade de venda)
- div = 0,25 
- Corretagem = 10,0

> $100 * 27,93 = 2.793$ 
> 
> $100 * 35,73 = 3.573$
> 
> $100 * 0,25 = 25,00$
> 
> $Lucro = (3.573 + 25,00) - 2.793 - 10,0 = 795,00$
> 
> $RS = log(3.573 + 25 - 10)/(2.793 + 10) * 100$ -> 24,69% 

### Taxa de Retorno Carteira

Pesos de cada Ativo:
- TOTS3 = 0,5
- WEGE3 = 0,5

> $27,47 * 0,5$ -> 13,73%
> 
> $11,17 * 0,5$ -> 5,58% 

Retorno da Carteira = 13,73 + 5,58 -> 19,31%

# Mede estatisticamente a dispersão relativa, risco por unidade de retorno. Quanto maior o CV, maior o risco. É muito útil na
# comparação dos riscos de ativos com retornos esperados diferentes

###############################
### Coeficiente de variação ###
###############################


#########################
### Índice de Treynor ###
#########################

########################
### Índice de Sharpe ###
########################




### CAPM (Capital Asset Pricing Model)
> É um modelo financeiro utilizado para determinar a taxa de retorno esperada de um investimento, dado o risco em relação ao mercado

$R1 = Rf + \beta1 * (Rm - Rf)$

- R1 = Retorno esperado
- Rf = Risk Free (Ativo Livre de Risco)
- $\beta1$ = beta da empresa
- Rm = Risco de Mercado
