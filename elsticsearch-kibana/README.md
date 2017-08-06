# elsticsearch-kibana

Elsticsearch-kibana is an elk construction environment for performance testing.
I wrote "elk", but since logstash is not used, it is not included.

I referred to this <https://github.com/deviantony/docker-elk>.


## Warrning

If running in linux environment you need to type the following command.
Otherwise elasticseatch will not start.

```:shell
sysctl -w vm.max_map_count=262144
```

It is a change to increase the number of memory maps that one process can hold.
There is probably no adverse effect on other software.