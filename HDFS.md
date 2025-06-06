

- **HDFS** este sistemul de fișiere distribuit folosit de [[Hadoop]] pentru a stoca volume uriașe de date pe un cluster de noduri.
- Împarte fișierele mari în blocuri (default 128MB/256MB) și le distribuie pe mai multe mașini, cu replicare automată (implicit 3 copii).
- Are o arhitectură master-slave: un [[NameNode]] central care gestionează metadatele și mai multe [[DataNode]]-uri care stochează datele efective.
- Este optimizat pentru acces **secvențial**, nu pentru fișiere mici sau acces aleator.
- Reprezintă coloana vertebrală a stocării în ecosistemul [[Big Data]]
v