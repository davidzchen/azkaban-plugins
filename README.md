Azkaban Plugins [![Build Status](http://img.shields.io/travis/azkaban/azkaban-plugins.svg?style=flat)](https://travis-ci.org/azkaban/azkaban-plugins)
===============

Building from Source
--------------------

To build Azkaban plugins from source:

```
./gradlew distTar
```

The above command builds all Azkaban plugins and packages them into GZipped Tar archives. To build Zip archives, run:

```
./gradlew distZip
```

Packages will be available in <code>/build/distributions</code>.


Documentation
-------------

For all Azkaban Plugins documentation, please see the [Azkaban Project Site](http://azkaban.github.io/)
