# SERVICE(Not finished yet)

* subject [here](./subject.md)

# How to use:
* in bash
```
cd service && docker build -t service . && docker run -it -p 443:443 -p 80:80 --rm service && docker rmi service
```
* in another window
```
curl -XPOST -d'{"animal":"cow", "sound":"moooo", "count": 3}' http://localhost/
```
