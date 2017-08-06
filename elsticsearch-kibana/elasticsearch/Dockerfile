FROM elasticsearch:5

RUN  echo "y" | /usr/share/elasticsearch/bin/elasticsearch-plugin install x-pack

USER elasticsearch

CMD ["-E", "network.host=0.0.0.0", "-E", "discovery.zen.minimum_master_nodes=1"]
