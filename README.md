# krofn-packs

Каталог сборок и манифесты для [KROFN Launcher](https://github.com/KROFN).

- `catalog.json` — список сборок (формат: `schemaVersion: 1`, см. пример в лаунчере `examples/catalog.example.json`).
- Манифесты и файлы сборок лежат в Release assets каждого тега `krofn-test-vX.Y.Z`.

## Права на файлы

В этой сборке нет файлов Minecraft (jar/ассеты Mojang) и сторонних модов.
Все моды (`krofn-testmod-*`) — собственные заглушки KROFN (MIT), созданные
специально для тестирования лаунчера.

## Как обновить каталог

После публикации новой версии через `pack-cli publish` (см. README лаунчера)
обновите `latestVersion` и `manifestUrl` в `catalog.json`.
