Os seguintes arquivos estão disponíveis:

1. Dataset do Comprasnet: DB_Collusion_Brazil_Comprasnet_processed.csv
Possui as seguintes colunas:
Bid_value (Brazilian real), Tender, Bid (bid's number of the tender), Competitors, Difference Bid/PTE, Date, Pre-Tender Estimate (PTE), Collusive_competitor, Number_bids, ipgQuantidade(quantidade licitada), especificidade, frequencia, material, Winner, Collusive_competitor_original(Collusive_competitor) e as screening variables (CV, SPD, DIFFP, RD, KURT, SKEW, KSTEST).

2. Collusion_Detection_Code.ipynb
Jupyter Notebook adaptado do script do estudo original, utilizado para analisar o dataset colusivo e gerar os dados apresentados no artigo.

3. dadoscomprasnetpunidosAjustado.ipynb
Jupyter Notebook com o script que gera o dataset do comprasnet e calcula as screens.

NOTAS:
Informações complementares comuns aos datasets são encontradas no estudo de García Rodríguez et al.(2022).