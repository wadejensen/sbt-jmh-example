# sbt-jmh-example

Example project for sbt-jmh, sbt plugin for JMH (Java Microbenchmark Harness).
Project is just a vanilla Scala project to let you modify the code and hit the ground running with sbt-jmh.

"Trust no one, bench everything." - [http://kto.so]
Plugin located at [https://github.com/ktoso/sbt-jmh]

Benchmark code taken directly from [http://chariotsolutions.com/blog/post/microbenchmarking-scala-with-jmh/]

Requirements:

*JDK
*SBT

```
# To run benchmark, call jhm:run from the sbt console in the project directory (root dir of this repo)
sbt
jmh:run -i 20 -wi 10 -f1 -t1
# close sbt console with 'exit'
```

Please see sources above for full explanation of flags and usage.

