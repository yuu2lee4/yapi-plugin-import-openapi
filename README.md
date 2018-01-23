# yapi-plugin-import-openapi 

openapi导入插件(仅支持3.0)，配置方法如下：   

第一步： 在生成的配置文件config.json中加入如下配置：  

```
"plugins": [
    {
      "name": "import-openapi",
      "options": {
      }
    }
  ]
```   

第二步：在config.json 这层目录下运行 ```yapi plugin --name yapi-plugin-import-openapi ```   重新下载插件  

第三步： 重启服务器

