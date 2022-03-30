# Fidenza-NFTs-Tableau-Dashboard
This repository shows how I collected &amp; prepared the data for my <a href="https://public.tableau.com/app/profile/trang.vo8254/viz/Fidenza_Full_Dashboard/FIDENZADASHBOARD"> Tableau dashboard on the Fidenza NFT collection</a>.

Data sources & Python Notebooks:

- `Fidenza trades` on the Ethereum blockchain: queried from this <a href="https://evgemedvedev.medium.com/ethereum-blockchain-on-google-bigquery-283fb300f579"> Ethereum public dataset </a> built and hosted by Google BigQuery. A Python notebook with all steps will be added shortly.
- `ETHUSD rates` by minute: extracted via the <a href="https://docs.coinapi.io/?python#timeseries-data-get"> free API </a> provided by CoinAPI. A Python notebook with all the steps will be added shortly.
- `Fidenza metadata` containing trait values: scraped directly from the token URIs, see this <a href="https://nbviewer.org/github/trang-h-vo/Fidenza-NFTs-Tableau-Dashboard/blob/main/Fidenza_metadata_extraction_EDA.ipynb"> Python notebook </a> for more details.

##### Libraries used: 
- `BeautifulSoup`
- `request`
- `pandas`, `matplotlib`, etc. 

