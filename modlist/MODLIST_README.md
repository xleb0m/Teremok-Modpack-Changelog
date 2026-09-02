🇬🇧 [English](#english) | 🇷🇺 [Русский](#русский)

---

## English

# Mod List Hub

This page is the entry point for browsing the modpack's mod list — the full table and every category breakdown.

### Full list

📋 **[modlist.md](../modlist.md)** — every mod in the pack, one table, all categories mixed together.

### Browse by category

| Category | Description |
|----------|-------------|
| [Magic](./magic.md) | Magic mods — spellcasting, rituals, mana systems, occult mechanics |
| [Technology](./technology.md) | Tech/automation mods — machines, power generation, industrial processing |
| [Library](./library.md) | API/library mods required by other mods; usually add no player-facing content themselves |
| [Performance](./performance.md) | Optimization mods — FPS improvements, chunk loading, memory/CPU usage |
| [Utility](./utility.md) | Quality-of-life tools — recipe viewers, maps, inventory management, info overlays |
| [Adventure](./adventure.md) | Exploration/RPG content — dungeons, bosses, quests, new dimensions |
| [World Generation](./world-generation.md) | New biomes, structures, terrain features |
| [Food](./food.md) | Cooking, farming, and food-related content |
| [Storage](./storage.md) | Storage solutions — chests, backpacks, item/fluid management |
| [Transportation](./transportation.md) | Movement — teleportation, vehicles, elevators, travel tools |
| [Decoration](./decoration.md) | Purely cosmetic blocks/items with no gameplay impact |
| [Equipment](./equipment.md) | Armor, tools, and weapons |
| [Mobs](./mobs.md) | New creatures/entities |
| [Social](./social.md) | Multiplayer-focused tools — chat, teams, communication |
| [Game Mechanics](./game-mechanics.md) | Changes to core vanilla systems, not tied to a specific theme |
| [Minigame](./minigame.md) | Standalone minigames |
| [Misc](./misc.md) | Anything that doesn't fit cleanly elsewhere |
| [Unknown](./unknown.md) | Not yet classified — pending manual review |

*A category file only exists once at least one mod has been sorted into it — an empty category has no page yet.*

### Versioning

The pack follows a custom versioning scheme suited to a testers-only, multi-stage build cycle:

```
s<season>-<stage>.<major>.<minor>.<patch>+build.<N>
```

| Part | Meaning |
|------|---------|
| `s<season>` | Season number, fixed for the pack's whole lifecycle (currently **Season 2**) |
| `<stage>` | Current readiness stage: `pre-alpha` → `alpha` → `beta` → `release` |
| `major.minor.patch` | Resets with each new stage. `major` = structural overhaul, `minor` = mods added/removed or new bridges, `patch` = balance/config/bugfixes |
| `+build.<N>` | Sequential build counter, incremented by exactly 1 on every release regardless of what changed |

Example progression:
```
s2-pre-alpha.0.1.0+build.1
s2-pre-alpha.0.1.1+build.2   <- balance patch
s2-pre-alpha.0.2.0+build.3   <- new mod added
s2-alpha.1.0.0+build.4        <- stage promoted to alpha
```

Full release history with dates lives in [CHANGELOG.md](../CHANGELOG.md).

---

## Русский

# Хаб списка модов

Эта страница — точка входа для навигации по списку модов сборки: полная таблица и разбивка по всем категориям.

### Полный список

📋 **[modlist.md](../modlist.md)** — все моды сборки в одной таблице, все категории вперемешку.

### Просмотр по категориям

| Категория | Описание |
|-----------|----------|
| [Magic](./magic.md) | Магические моды — заклинания, ритуалы, системы маны, оккультные механики |
| [Technology](./technology.md) | Технические/автоматизационные моды — машины, генерация энергии, промышленная обработка |
| [Library](./library.md) | API/библиотечные моды, необходимые другим модам; обычно сами не добавляют игрового контента |
| [Performance](./performance.md) | Моды оптимизации — улучшение FPS, загрузка чанков, использование памяти/CPU |
| [Utility](./utility.md) | Инструменты для удобства — просмотр рецептов, карты, управление инвентарём, информационные оверлеи |
| [Adventure](./adventure.md) | Контент для исследования/RPG — подземелья, боссы, квесты, новые измерения |
| [World Generation](./world-generation.md) | Новые биомы, структуры, особенности рельефа |
| [Food](./food.md) | Готовка, фермерство и контент, связанный с едой |
| [Storage](./storage.md) | Решения для хранения — сундуки, рюкзаки, управление предметами/жидкостями |
| [Transportation](./transportation.md) | Перемещение — телепортация, транспорт, лифты, инструменты для путешествий |
| [Decoration](./decoration.md) | Чисто косметические блоки/предметы без влияния на геймплей |
| [Equipment](./equipment.md) | Броня, инструменты и оружие |
| [Mobs](./mobs.md) | Новые существа/сущности |
| [Social](./social.md) | Инструменты для мультиплеера — чат, команды, коммуникация |
| [Game Mechanics](./game-mechanics.md) | Изменения базовых ванильных систем, не привязанные к конкретной теме |
| [Minigame](./minigame.md) | Самостоятельные мини-игры |
| [Misc](./misc.md) | Всё, что не вписывается чётко в другие категории |
| [Unknown](./unknown.md) | Ещё не классифицировано — ожидает ручной проверки |

*Файл категории появляется только тогда, когда в неё попал хотя бы один мод — у пустой категории пока нет страницы.*

### Версионирование

Сборка использует собственную схему версионирования, подходящую под многостадийный цикл разработки только для тестеров:

```
s<сезон>-<стадия>.<major>.<minor>.<patch>+build.<N>
```

| Часть | Значение |
|-------|----------|
| `s<сезон>` | Номер сезона, фиксирован на весь жизненный цикл сборки (сейчас — **Сезон 2**) |
| `<стадия>` | Текущая стадия готовности: `pre-alpha` → `alpha` → `beta` → `release` |
| `major.minor.patch` | Обнуляется при смене стадии. `major` = структурная переработка, `minor` = добавлены/убраны моды или новые мосты, `patch` = баланс/конфиги/багфиксы |
| `+build.<N>` | Сквозной счётчик билдов, увеличивается ровно на 1 при каждом релизе, независимо от того, что изменилось |

Пример прогрессии:
```
s2-pre-alpha.0.1.0+build.1
s2-pre-alpha.0.1.1+build.2   <- патч баланса
s2-pre-alpha.0.2.0+build.3   <- добавлен новый мод
s2-alpha.1.0.0+build.4        <- переход на стадию alpha
```

Полная история релизов с датами — в [CHANGELOG.md](../CHANGELOG.md).
