# OPEN COBOL project

## Install GNU COBOL in Linux (can use WSL in Windows)
```
> sudo apt get gnucobol
> cobc --version
```

## Complile and create executable
```
> cobc -x src/COBBAT/PINVRPT.cbl -o output/executables/PINVRPT
```

## Run Executable
```
> output/executables/PINVRPT
```