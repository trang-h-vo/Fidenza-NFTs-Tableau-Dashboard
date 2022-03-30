# Fidenza-NFTs-Tableau-Dashboard
This repository shows how I collected &amp; prepared the data for my <a href="https://public.tableau.com/app/profile/trang.vo8254/viz/Fidenza_Full_Dashboard/FIDENZADASHBOARD"> Tableau dashboard on the Fidenza NFT collection</a>.

Datasets & sources:

1. `Fidenza trades` on the Ethereum blockchain: queried from this <a href="https://evgemedvedev.medium.com/ethereum-blockchain-on-google-bigquery-283fb300f579"> Ethereum public dataset </a> built and hosted by Google BigQuery.
2. `ETHUSD rates` by minute: extracted via the <a href="https://docs.coinapi.io/?python#timeseries-data-get"> free API </a> provided by CoinAPI. 
3. `Fidenza metadata` containing trait values: scraped from the token URIs, see this <a href="https://nbviewer.org/github/trang-h-vo/Fidenza-NFTs-Tableau-Dashboard/blob/main/Fidenza_metadata_extraction_EDA.ipynb"> Python notebook </a> for more details.


All the Python code & datasets used in the Tableau Dashboard are stored in this repository. 

To get a quick view of the notebooks, see here: <a href="https://nbviewer.org/github/trang-h-vo/Fidenza-NFTs-Tableau-Dashboard/blob/main/Fidenza_trades_ETH_from_Goggle_BigQuery.ipynb"> part 1</a>, <a href="https://nbviewer.org/github/trang-h-vo/Fidenza-NFTs-Tableau-Dashboard/blob/main/ETHUSD_rates_from_CoinAPI.ipynb"> part 2</a> - *work in progress*, and <a href="https://nbviewer.org/github/trang-h-vo/Fidenza-NFTs-Tableau-Dashboard/blob/main/Fidenza_metadata_extraction_EDA.ipynb"> part 3</a>.



##### Libraries used: 
- BeautifulSoup
- request
- pandas, matplotlib and so on. 

Last update: Mar 30, 2022.
