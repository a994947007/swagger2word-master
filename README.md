# swagger2word-master
swagger2在线文档转word文档

## 使用方式
 · 在appliaction.yml中填写swagger在线文档的地址或者填写swagger生成的json文档的地址。
如：swagger.url: http://localhost:8081/v2/api-docs
swagger.url: D:/swagger.json

· 在http url中直接传递swagger.json的地址
http://127.0.0.1:8080/toWord?url=https://petstore.swagger.io/v2/swagger.json
