# Task 2
5140904/40102 Петунин Антон Александрович 

### Необходимо быть в ветке Task_2!!!

```sh
git checkout Task_2
```

### Build

```sh
make
```
```sh
make install
```

### Команды для проверки

```sh
tail -f /var/log/foxweb.log
```
```sh
journalctl -t PICOFoxweb -e
```

### Destroy build

```sh
make uninstall
```
