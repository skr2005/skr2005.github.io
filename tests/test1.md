---
permalink: /tests/test1.html
title: TEST
---
以下是一个示例


```
<html><head><meta name="viewport" content="width=device-width,initial-scale=1.0, minimum-scale=0.5, maximum-scale=3.0, user-scalable=yes"/>   <title>nmsl</title></head><body><p id=1 style="word-wrap:break-word;word-break:break-all;"</p><script>
    
    function repeatStringNumTimes(string, times) { var repeatedString = ""; while (times > 0) { repeatedString += string; times--; } return repeatedString; }
    
    document.getElementById(1).innerHTML = repeatStringNumTimes("Hello!",25000)
</script></body></html>
```
