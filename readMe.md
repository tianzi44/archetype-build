 ####生成Catalog文件
 ```mvn archetype:crawl```
 
 构建成功之后，本地仓库目录下将会生成一个archetype-catalog.xml文件,如下，有两个archetype，一个是自定义的，一个是插件自己的
 <br>
 
 ####生成目标项目结构
 ```mvn archetype:generate -DarchetypeCatalog=local```
 
 插件默认的catalog的路径为remote,local，即远程仓库和本地仓库的，为了构建的速度，直接将catalog的路径设置为本地仓库
 
 
 