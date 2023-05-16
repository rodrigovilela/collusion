Os seguintes arquivos estão disponíveis:

1. Dataset do Comprasnet: DB_Collusion_Brazil_Comprasnet_processed.csv
Possui as seguintes colunas:
Bid_value (Brazilian real), Tender, Bid (bid's number of the tender), Competitors, Difference Bid/PTE, Date, Pre-Tender Estimate (PTE), Collusive_competitor, Number_bids, ipgQuantidade(quantidade licitada), especificidade, frequencia, material, Winner, Collusive_competitor_original(Collusive_competitor) e as screening variables (CV, SPD, DIFFP, RD, KURT, SKEW, KSTEST).

2. Dataset composto pelos campos comuns dos datasets do estudo base e do Comprasnet: DB_Collusion_All-Comprasnet_processed.csv
Tender, Bid_value (Euro), Winner, Number_bids, Collusive_competitor, CV, SPD, DIFFP, RD, KURT, SKEW, KSTEST, Dataset

3. Collusion_Detection_Code.ipynb
Jupyter Notebook adaptado do script do estudo original, utilizado para analisar o dataset colusivo e gerar os dados apresentados no artigo.

4. dadoscomprasnetpunidosAjustado.ipynb
Jupyter Notebook com o script que gera o dataset do comprasnet e calcula as screens.

NOTAS:
Informações complementares comuns aos datasets são encontradas no estudo de García Rodríguez et al.(2022).
Os valores dos lances do Comprasnet agregados ao DB_Collusion_All-Comprasnet_processed.csv foram convertidos na contação 1R$ (0,15€).
