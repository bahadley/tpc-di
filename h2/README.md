H2 Database Engine
------------------

H2 [Home](http://h2database.com/html/main.html)

How to start the server in H2.
----------------------------------

```
# java -cp /opt/h2/bin/h2*.jar org.h2.tools.Server \
  -tcp -tcpPort 9101 -tcpAllowOthers -baseDir /var/lib/h2/data
```


How to start a client shell in H2.
----------------------------------

`$ java -cp /opt/h2/bin/h2*.jar org.h2.tools.Shell`   

Enter a URL with appropriate IP address when prompted:   

`jdbc:h2:tcp:192.168.001.001:9101/tpcdi`
