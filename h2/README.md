## H2 Database Engine

H2 [Home](http://h2database.com/html/main.html)


How to start the H2 server:
---------------------------

```
# java -cp /opt/h2/bin/h2*.jar org.h2.tools.Server \
  -tcp -tcpPort 9101 -tcpAllowOthers -baseDir /var/lib/h2/data
```

How to start a H2 client shell:
-------------------------------

`$ java -cp /opt/h2/bin/h2*.jar org.h2.tools.Shell`   

Enter a URL with appropriate IP address when prompted:   

`jdbc:h2:tcp:192.168.001.001:9101/tpcdi`
