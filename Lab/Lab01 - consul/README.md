# Lab01 - consul

---

## ps1
````ps1
# --rm automatically remove the container
# -i -- run an init inside the container
# -t -- allocate a pseudo-tty
docker container run --rm -it consul
````
[<img src="https://i.imgur.com/Yr6whAq.png">](https://i.imgur.com/Yr6whAq.png)

---

## Test
````ps1
curl 127.0.0.1:8500

curl : Unable to connect to the remote server
````

---

## port public in container
````ps1
# -p portHost:portContainer
docker container run -rm -it -p 8500:8500 consul
````
[<img src="https://i.imgur.com/UWBMLgT.png">](https://i.imgur.com/UWBMLgT.png)
* test url again:
````ps1
# IE not exist anymore
Set-ItemProperty -Path "HKLM:\SOFTWARE\Microsoft\Internet Explorer\Main" -Name "DisableFirstRunCustomize" -Value 2

PS C:\Users\paul> curl 127.0.0.1:8400                                              

StatusCode        : 200
````
