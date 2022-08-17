# weather-cli

Aplicativo por linha de comando  desenvolvido em GoLang para obter os dados do clima

## Instalação

## Sintaxe

```
weather [-options] [args]
```

## Opçoes

| Opção | Descrição |
|-------|-----------|
|   -l    |   Definir a localização padrão        |
|   -h12   |     Obter o tempo das próximas 12 horas      |
|   -h24   |     Obter o tempo das próximas 24 horas      |
|   -w   |     Obter o tempo da próxima semana      |
|   -help   |     Obter ajuda      |
|   -version   |     Obter a versão      |

## Exemplos de uso

Definir a localização padrão

```
weather -l joinville
```

Obter o tempo do dia da localização padrão
```
weather
```

Obter o tempo do dia de qualquer localização
```
weather curitiba
```

Obter o tempo das próximas 24 horas
```
weather -h12
```

Obter o tempo das próximas 24 horas
```
weather -h24
```

Obter o tempo da próxima semana
```
weather -w
```

Obter ajuda
```
weather -version
```

Obter a versão
```
weather -help
```

