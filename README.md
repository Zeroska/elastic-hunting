# Elasticsearch Crawler

After you found the target ELK -> which by using censys and shodan to actually crawl from them, mostly that Elasticsearch instance is on port 9200 and Kibana is using nghinx and 
host on port 5601, by crafting an query on censys for both of these

-> we can find an IP address, and input it into this tool to actually crawl from them

You may ask why should I do this, is it the Elastic has already block this type of action, by access elasticsearch instance by using  http://ipaddress:port/_cat/indices?v, Yes I do aware of such thing
but here a thing, most likely the guy who configure ELK stack will make a mistake and when those mistake happen, we will be on the first ship to warn them or to get the data from them, 

Threat Actor do make mistake, hunting for their ELK stack is also viable

## Overview

I will insert flowchart or control flow soon

## Installation and Configuration

If you are on Mac you would use brew to install 

```shell
brew install masscan
```

Install python dependancy

```shell 
pip3 install -r requirement.txt
```

Running the scripts
```shell
chmod +x scan.sh
./scan.sh
```