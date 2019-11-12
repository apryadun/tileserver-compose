# TileServer GL in docker-compose

This docker-compose project is based on [TileServer GL](https://github.com/maptiler/tileserver-gl) just wrapping around it the ease of docker-compose. 
# Steps to launch
1. Download ```.mbtiles``` file and place it under the ```./data/``` directory. If started without any file a sample one will be downloaded automatically (zurich_switzerland.mbtiles)
2. Launch the stack:
```
docker-compose up -d
```
3. To check the service is up navigate to ```http://<node-ip>:8880```. To see logs execute:
```
docker-compose logs -f
```

