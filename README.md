# AcElo v2.7 — Лучшая ELO-система 2025 года

[![Spigot](https://img.shields.io/badge/Spigot-1.16--1.21-brightgreen)](https://spigotmc.org)
[![Version](https://img.shields.io/badge/Version-2.7-blue)](https://github.com/maks1ch/AcElo/releases)
[![Downloads](https://img.shields.io/github/downloads/maks1ch/AcElo/total)](https://github.com/maks1ch/AcElo/releases)

Самая красивая, быстрая и настраиваемая ELO + ранги система!

## Особенности
- Полностью настраиваемые ранги с градиентами и HEX-цветами
- Все сообщения в config.yml
- Команды: `/acelo reload`, `/acelo reset <ник>`, `/acelo reset all`
- Полный таб-комплит
- Поддержка PlaceholderAPI (%acelo_elo%, %acelo_rank%)
- Сохранение в data.yml

## Как создать красивый ТОП-10 по ELO (DecentHolograms / HolographicDisplays)

1. Установи плагины:
   - [PlaceholderAPI](https://spigotmc.org/resources/6245/) (для работы плагина он нужен тоже)
   - [DecentHolograms](https://modrinth.com/plugin/decentholograms) ИЛИ [HolographicDisplays](https://dev.bukkit.org/projects/holographic-displays)

2. Перезагрузи сервер (или выполни `/papi reload AcElo`)

3. Создай голограмму командой:
   - DecentHolograms: `/dh create elo_top`
   - HolographicDisplays: `/hd create elo_top`

4. Отредактируй голограмму (пример для DecentHolograms):

```yaml
Заходите в плагин DecentHolograms/HolographicDisplays
И вставляйте те строки которые идут после lines:
Lines:
  - "§x§F§F§C§C§0§0§l▎ ТОП-10 ПО ELO ▎"
  - ""
  - "1. %acelo_top_name_1% §8┃ §f%acelo_top_elo_1% ELO"
  - "2. %acelo_top_name_2% §8┃ §f%acelo_top_elo_2% ELO"
  - "3. %acelo_top_name_3% §8┃ §f%acelo_top_elo_3% ELO"
  - "4. %acelo_top_name_4% §8┃ §f%acelo_top_elo_4% ELO"
  - "5. %acelo_top_name_5% §8┃ §f%acelo_top_elo_5% ELO"
  - "6. %acelo_top_name_6% §8┃ §f%acelo_top_elo_6% ELO"
  - "7. %acelo_top_name_7% §8┃ §f%acelo_top_elo_7% ELO"
  - "8. %acelo_top_name_8% §8┃ §f%acelo_top_elo_8% ELO"
  - "9. %acelo_top_name_9% §8┃ §f%acelo_top_elo_9% ELO"
  - "10. %acelo_top_name_10% §8┃ §f%acelo_top_elo_10% ELO"
  - ""
```
## Установка
1. Скачиваем сам плагин [Releases]([https://github.com/ТВОЙ_НИК/AcElo/releases](https://github.com/ichmaks1ch/AcElo/releases)).
2. Кидаем `AcElo.jar` в папку plugins
3. Перезапускаем сервер
4. Настраиваем config.yml под себя
5. PROFIT!

## Связь с создателем
- Мой телеграм: [Telegram]([https://t.me/maksonov_v])
- Мой дискорд: [maks1ch_v_bane]
**Твой пвп сервер станет лучше с AcElo**
