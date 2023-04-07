Elaticsearch backup

1. Install elaticdump

npm install -g elasticdump
2. Run dump

elasticdump --input http://localhost:9200/my-data --output backup-my-data.json --type=data --size=-1
