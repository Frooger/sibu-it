## Access Docker Ports with limited recources
You can access docker container ports by enter the created network interface on 
root for specfic container.

```
nsenter --target <nginx's PID> --net
```
```
curl http://localhost:80
```
