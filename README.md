# ziplineStudy
source /var/root/anaconda3/bin/activate

source activate env_zipline

QUANDL_API_KEY=<api-key> zipline ingest -b quandl
