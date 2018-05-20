## Change timezone for container running
```export  TZ=Asia/Ho_Chi_Minh``` <br>

```ls /usr/share/zoneinfo/Asia/Ho_Chi_Minh ```

```ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone```
