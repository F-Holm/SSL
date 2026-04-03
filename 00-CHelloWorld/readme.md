# 00-CHelloWorld

## Compilador

`GCC`

## Versión

```bash
gcc (Ubuntu 13.3.0-6ubuntu2~24.04.1) 13.3.0
Copyright (C) 2023 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```

## Versiones de C soportadas

- `c90`
- `c99`
- `c11`
- `c17`
- `c2x`

(Existen muchas más versiones que se pueden poner en la flag `-std=` del compilador pero son iguales a alguna de las que están acá)

## Versión de C utilizada

`c2x`

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
