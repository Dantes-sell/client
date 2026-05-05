# Dantes Client Pack (Fabric 1.21.4)

Этот репозиторий подготавливает локальный runtime с Fabric 1.21.4 и сразу кладет мод Dantes в `runtime/mods`.

## Что внутри
- `mods/dantes-client-1.21.4.jar` — мод клиента
- `build.gradle` — задачи скачивания/установки

## Требования
- Java 21
- Windows / PowerShell

## Запуск
```powershell
./gradlew.bat setupClient
```

После выполнения:
- Fabric установлен в `runtime`
- Мод лежит в `runtime/mods`

Далее можно запускать Minecraft/Fabric с game directory = `runtime`.
