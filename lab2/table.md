WSL
=
\      | SSE   | AVX
-------|-------|-----
O0     |235605 | 311620
O1     |50177  | 76860
O2     |65336  | 88999
O3     |24852  | 48320
O4     |26099  | 50350
Ofast  |26541  | 50815

Windows
=
\      | SSE   | AVX
-------|-------|-----
O0     |214900 | 76563
O1     |40993  | 28234
O2     |51986  | 22885
O3     |22995  | 21854
O4     |25062  | 23030
Ofast  |25059  | 28225

# поизучать кол-во тактов на инструкцию

# gcc говно, clang чётко (посмотреть разницу в компиляторах)

# найти тачку поиграться с fma3 и avx512

# дать лабу на load balancing (3 прокси менеджера формата nginx, traefic, apache) (и разные БД формата PGsql, redis, cassandra, mysql, mongo, sqlite) и дать на них нагрузку каким нить JMeter, Gatling, Locust, чтобы у каждого был свой вариант

# курс по докеру и оркестрации у нас будет, на эту тему не думает

# сравнить дизассемблер C, Go, Rist и Zig. Возможно там будет что-то интересное. Да и свой performace test провести можно в конце концов то.

# performance оптимизация баз данных на примере PGsql, тест разных типов БД для разных задач

# Разработать и протестировать механизм кэширования данных в веб-приложении с использованием Redis или Memcached. Используйте реальные данные или сгенерируйте их для имитации нагрузки. Сравните производительность при использовании кэша и без него (основныя задача - поддержка консистентности кэша и очистка его от лишних данных)