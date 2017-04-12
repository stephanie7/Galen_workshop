#Requirements
 For Galen you need to have a Java version 1.8 or greater installed. If you don’t have Java you can install it from official website
 * Java 8 
 * NPM
 
 #NPM-based Installation
If you’re using NPM you can just install galen via the following command
 ```
sudo npm install -g galenframework-cli
```
#Run Test Commonds
 ```
open the geckdriver file in the iterm 
```

```
galen check demo.gspec --url "http:www.baidu.com" --size "1024x768" --htmlreport "report1"
```
```
galen test p4ep.test --htmlreport "report2"
```
```
galen test builder.test --htmlreport "report3"
```

If something with your browser diriver, you can change the default driver:
with the commond :
```
galen config
```
Change the browser to other browser: 
It support: firefox, chrome, ie, phantomjs, edge
