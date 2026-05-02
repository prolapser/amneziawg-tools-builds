# amneziawg-tools-builds

Автоматические сборки [amneziawg-tools](https://github.com/amnezia-vpn/amneziawg-tools).

## Linux

| Libc  | Архитектура | Файл                                                                                                                                |
|-------|-------------|-------------------------------------------------------------------------------------------------------------------------------------|
| glibc | x64         | [linux-ubuntu-x64.tar.gz](https://github.com/prolapser/amneziawg-tools-builds/releases/latest/download/linux-ubuntu-x64.tar.gz)     |
| glibc | arm64       | [linux-ubuntu-arm64.tar.gz](https://github.com/prolapser/amneziawg-tools-builds/releases/latest/download/linux-ubuntu-arm64.tar.gz) |
| musl  | x64         | [linux-alpine-x64.tar.gz](https://github.com/prolapser/amneziawg-tools-builds/releases/latest/download/linux-alpine-x64.tar.gz)     |

### Содержимое Linux-архивов

- `awg` — основной инструмент управления AmneziaWG
- `awg-quick` — скрипт быстрой настройки интерфейса

### Пример установки:

```bash
curl -sL https://github.com/amnezia-vpn/amneziawg-tools-builds/releases/latest/download/linux-ubuntu-x64.tar.gz | tar -xzC /tmp && sudo install -m 755 /tmp/awg /tmp/awg-quick /usr/local/bin/ && rm /tmp/awg /tmp/awg-quick
```

## Windows

| Архитектура | Файл                                                                                                                |
|-------------|---------------------------------------------------------------------------------------------------------------------|
| x64         | [windows-x64.zip](https://github.com/prolapser/amneziawg-tools-builds/releases/latest/download/windows-x64.zip)     |
| x86         | [windows-x86.zip](https://github.com/prolapser/amneziawg-tools-builds/releases/latest/download/windows-x86.zip)     |
| arm64       | [windows-arm64.zip](https://github.com/prolapser/amneziawg-tools-builds/releases/latest/download/windows-arm64.zip) |

### Содержимое Windows-архивов

- `awg` — основной инструмент управления AmneziaWG

> SHA256-суммы всех файлов — в [SHA256SUMS.txt](https://github.com/prolapser/amneziawg-tools-builds/releases/latest/download/SHA256SUMS.txt)
