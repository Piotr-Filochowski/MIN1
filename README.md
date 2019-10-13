# Praca domowa z przedmiotu Metody i narzędzia wspomagania decyzji LAB 1

autor: Piotr Filochowski, I6E2S1

## Instalacja go

https://golang.org/doc/install?download=go1.13.1.windows-amd64.msi


### Biblioteka

Instalacja biblioteki gonum:

```
go get -u -t gonum.org/v1/gonum/...
```

### Instalacja rozwiązania:

1. Zainstalować gonum.
2. Ustawić wartość zmiennej środowiskowej GOPATH
3. W folderze na który wskazuje GOPATH utworzyć foldery: bin, pkg, src
4. W folderze src utworzyć folder pfilochowski a w nim umieścić plik z kodem źródłowym min1.go


## Kompilacja i uruchomienie

W folderze %GOPATH%/src/pfilochowski uruchomić w cmd:

```
go run ./min1.go
```

Oczekiwany rezultat:

opt: -8
x: [2 3 0 0]

