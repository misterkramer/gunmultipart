# Кастомная пушка на основе Pandora

Исходники [Pandora](https://github.com/yandex/pandora/)

[![Read the Docs](https://readthedocs.org/projects/yandexpandora/badge/)](https://readthedocs.org/projects/yandexpandora/)

## С чего начать

### Установить GO
[Install](https://golang.org/doc/install) Golang >= 1.8.3.

### Скачать Pandora
```bash
go get github.com/yandex/pandora
```

### Скачать и установить multipart_pandora
Просто переместите папку multipart_pandora в $GOPATH/src/github.com/yandex/pandora/examples/ и выполните:

```bash
cd $GOPATH/src/github.com/yandex/pandora/examples/multipart_pandora
go get .
```
После этого появится исполняемый файл с названием multipart_pandora в $GOPATH/bin

Запустите стрельбу:
```bash
multipart_pandora custom.yaml
```