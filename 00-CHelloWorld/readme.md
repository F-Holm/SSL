# 00-CHelloWorld

## Compilador

`Clang`

## Versión

```text
Ubuntu clang version 18.1.3 (1ubuntu1)
Target: x86_64-pc-linux-gnu
Thread model: posix
InstalledDir: /usr/bin
```

## Versiones de C soportadas

```text
use 'c89', 'c90', or 'iso9899:1990' for 'ISO C 1990' standard
use 'iso9899:199409' for 'ISO C 1990 with amendment 1' standard
use 'gnu89' or 'gnu90' for 'ISO C 1990 with GNU extensions' standard
use 'c99' or 'iso9899:1999' for 'ISO C 1999' standard
use 'gnu99' for 'ISO C 1999 with GNU extensions' standard
use 'c11' or 'iso9899:2011' for 'ISO C 2011' standard
use 'gnu11' for 'ISO C 2011 with GNU extensions' standard
use 'c17', 'iso9899:2017', 'c18', or 'iso9899:2018' for 'ISO C 2017' standard
use 'gnu17' or 'gnu18' for 'ISO C 2017 with GNU extensions' standard
use 'c23' for 'Working Draft for ISO C23' standard
use 'gnu23' for 'Working Draft for ISO C23 with GNU extensions' standard
```

## Versión de C utilizada

`c23`

`__STDC_VERSION__` = `202311`

## Comandos de Make

| Comando | Descripción |
| :--- | :--- |
| `make` | Alias de `make debug save run`. |
| `make debug` | Compila con símbolos de depuración (`-g`) y sin optimización. |
| `make release` | Compila con optimización máxima (`-O3`). |
| `make run` | Ejecuta el programa generado. |
| `make save` | Ejecuta el programa generado y guarda su salida en el [archivo de output](output.txt). |
| `make clean` | Elimina el ejecutable generado. |
| `make format` | Aplica `clang-format` con el estilo de Google. |
