[![Build Status](https://travis-ci.org/dilbertside/sigmajs.svg?branch=master)](https://travis-ci.org/dilbertside/sigmajs)

# sigmajs
WebJars Sigma.js

#Original library
https://github.com/jacomyal/sigma.js

#Made on the model of
http://www.webjars.org/contributing


#to install and run locally stable version
```
mvn install
```

example of use in a Spring managed Thymeleaf page
```
    <script th:src="@{/webjars/sigmajs/1.0.3/sigma.min.js}"></script>
    <script th:src="@{/webjars/sigmajs/1.0.3/plugins/sigma.parsers.gexf.min.js}"></script>
    <script th:src="@{/webjars/sigmajs/1.0.3/plugins/sigma.plugins.dragNodes.min.js}"></script>
    <script th:src="@{/webjars/sigmajs/1.0.3/plugins/sigma.layout.forceAtlas2.min.js}"></script>
```




#to test latest code from Sigma.js
```
git checkout 1.0.4
mvn install
```

Sigma source is in a sub folder src for easier debugging.

##pre-requisites for snapshot
you must have npm installed on your machine and in your path

##warning: 
if you are behind a proxy, no luck the maven ant plugin do not fetch the source code trivially
