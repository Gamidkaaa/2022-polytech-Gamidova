Какой процесс имеет наименьший идентификатор?

```
localhost:~# ps -Ao pid,comm | sort | head -n1
    1 init
```

Какой идетификтор у вашего текущего shell-процесса?

```
$ ps -p $$
      PID    PPID    PGID     WINPID   TTY         UID    STIME COMMAND
     1750    1749    1750       8712  pty0      197609 10:13:18 /usr/bin/bash

```

Сколько всего запущено процессов?

```
$ ps -a | wc -l
4
```
