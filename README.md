# Elasticsearch Crawler

After you found the target ELK -> which by using censys and shodan to actually crawl from them, mostly that Elasticsearch instance is on port 9200 and Kibana is using nghinx and 
host on port 5601, by crafting an query on censys for both of these

-> we can find an IP address, and input it into this tool to actually crawl from them

## Installation and Configuration

If you are on Mac you would use brew to install 

```shell
brew install masscan
```

Install python dependancy

```shell 
pip3 install -r requirement.txt
```

