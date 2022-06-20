# Mozzarella
Mozzarella modpack for minecraft 1.18.2 (fabric)

Tested with 7G of ram, with these jvm arguments:

-Xmx7G -Xms1G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=6 -XX:G1ReservePercent=6 -XX:MaxGCPauseMillis=10 -XX:G1HeapRegionSize=32M -XX:ParallelGCThreads=12 -XX:SoftRefLRUPolicyMSPerMB=10000 -Dsun.rmi.dgc.server.gcInterval=2147483648

Curently stable afaik, althought it does seem intensive on memory usage, even in main menu.

Pregenerating chunks with chunky (/chunky help) helps alot.

Please communicate any and all issues.