# Análise Exploratória de Dados de Vinhos Tintos

## Contexto

Como cientista de dados da área de *advanced analytics* em uma empresa especializada na distribuição e vendas de vinhos tintos, meu trabalho é ajudar a empresa a identificar quais vinhos podem ser percebidos como bons pela maioria do público. 

Recentemente, realizamos uma pesquisa em que oferecemos vinhos tintos, com diferentes características físico-químicas, a voluntários. Após experimentarem as amostras, eles atribuíram notas de 0 a 10 para cada vinho. 

A base coletada contém as seguintes informações:

### Medidas de 11 variáveis físico-químicas que caracterizam cada amostra:
1. **Fixed acidity**: medida da acidez devido à presença de ácidos orgânicos de baixa volatilidade (ácido málico, lático, tartárico ou cítrico) no vinho.
2. **Volatile acidity**: medida da acidez devido a ácidos de baixo peso molecular (sobretudo ácido acético) presentes no vinho, responsáveis pelo aroma e gosto de vinagre.
3. **Citric acid**: medida de ácido cítrico no vinho.
4. **Residual sugar**: medida de açúcar residual no vinho, oriundo dos resíduos de açúcar da uva que permanecem após a fermentação.
5. **Chlorides**: medida de cloretos (íons de cloro) no vinho.
6. **Free sulfur dioxide**: medida de dióxido de enxofre livre (não ligado a outras moléculas) no vinho.
7. **Total sulfur dioxide**: medida de dióxido de enxofre total (livre + porção ligada a outras moléculas) no vinho.
8. **Density**: medida da densidade do vinho.
9. **pH**: medida do pH do vinho.
10. **Sulphates**: medida de sulfatos (íons SO₄²⁻) no vinho.
11. **Alcohol**: medida da graduação alcoólica do vinho.

### Variável de resposta:
12. **Quality**: um *score* numérico de qualidade (de 0 a 10), baseado nos dados sensoriais fornecidos pelos voluntários.

## Objetivo

Com base nesses dados, meu objetivo é construir um modelo que consiga distinguir vinhos bons de ruins a partir das suas características físico-químicas. 

Este modelo será essencial para ajudar a empresa a tomar decisões mais direcionadas. Por exemplo, quando produtoras de vinho oferecerem um novo produto para venda, será possível decidir, de forma fundamentada, se vale a pena incluir esse vinho no nosso portfólio, com base na predição da sua qualidade pelo modelo.

## Meu Papel

Meu papel como cientista de dados é claro: **agregar valor ao negócio explorando os dados disponíveis.**  

Antes de construir o modelo, preciso realizar uma análise exploratória detalhada dos dados coletados. Isso inclui compreender as relações entre as variáveis, identificar padrões e preparar o terreno para as próximas etapas de modelagem. 

## Pergunta Principal

A principal pergunta que guiará essa análise é:  
**Como utilizar os dados disponíveis para no futuro, criar um sistema capaz de decidir se um vinho será vendido por nossa empresa ou não?**

Obs.: O enunciado acima foi apenas uma historinha que criei pra motivar o problema em um contexto de negócio. Para maiores informações sobre a coleta e origem real dos dados, veja a página do dataset no repositório UCI machine learning repository, disponível aqui - https://archive.ics.uci.edu/ml/datasets/wine+quality.