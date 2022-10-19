# commands

---

## List
|n|name|e.g.|O/P|
|-|----|----|---|
|0|images|docker images|[<img src="https://i.imgur.com/rvJwd1H.png">](https://i.imgur.com/rvJwd1H.png)|
|1|cli |# -i --interactive<br/> # -t --terminal?<br/> # anbry_wiles --imageName<br/>`docker container exec -i -t angry_wiles consul -help`|[<img src="https://i.imgur.com/RiMUEej.png">](https://i.imgur.com/RiMUEej.png)|
|2|compose.yml|`docker compose up`<br/>`docker compose down`<br/>#-d --detach <imageName> <br/>`docker compose up -d ships2`|[<img src="https://i.imgur.com/CUMAjk2.png">](https://i.imgur.com/CUMAjk2.png)<br/>detach image:<br/> [<img src="https://i.imgur.com/u5PVkHK.png">](https://i.imgur.com/u5PVkHK.png)|
|3|logs|`docker compose logs envc-shipments --follow -since 0s`||
|4|process|`docker compose ps`|[<img src="https://i.imgur.com/ax6Ttif.png">](https://i.imgur.com/ax6Ttif.png)|
|5|volume|docker volume ls||
|6|prune|# delete volume<br/> `docker volume prune`||
|7|system|docker system df||
