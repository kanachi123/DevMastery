# UE5 C++ GameDev Iceberg (Progression Levels)

---

## Уровень 0 — Я нажал Play в первый раз

### Чистые основы взаимодействия

**Механики:**
- Движение персонажа (WASD)
- Камера (mouse look)
- Прыжок
- Простое взаимодействие (E → Line Trace)
- Коллизии

**UE5 C++ сущности:**
- ACharacter
- UCharacterMovementComponent
- APlayerController

**Суть:**
Я умею управлять телом в мире

---

## Уровень 1 — Я могу трогать мир

### Первые игровые системы

**Механики:**
- Подбор предметов (Pickup)
- Двери / триггеры (Overlap Events)
- Система здоровья (HP)
- Урон по игроку и AI
- Простой UI (HP bar)

**UE5 C++:**
- AActor
- UActorComponent (HealthComponent)
- OnComponentBeginOverlap

**Суть:**
Мир реагирует на меня

---

## Уровень 2 — Системы начинают появляться

### Первые настоящие игровые системы

**Механики:**
- Инвентарь (TArray + structs)
- Оружие (equip / unequip)
- Статы (damage, speed, armor)
- Стрельба (LineTrace / Projectile)
- Cooldowns

**UE5 C++:**
- DataAssets / DataTables
- Struct-based items
- Component architecture

**Суть:**
Я собираю игру из систем

---

## Уровень 3 — Геймплейный цикл

### Игра начинает жить

**Механики:**
- Цикл: бой → награда → улучшение
- Прогрессия (XP / levels)
- Враги с патрулем
- Спавнеры
- Wave system

**UE5 C++:**
- GameMode / GameState
- Spawn system
- TimerManager

**Суть:**
Игра становится повторяемой

---

## Уровень 4 — Поведение и интеллект

### AI и реактивность мира

**Механики:**
- Патруль / преследование / атака
- Behavior Trees
- Perception system (Sight/Hearing)
- Cover system
- Тактика врагов

**UE5 C++:**
- Behavior Tree + Blackboard
- AIController
- AI Perception

**Суть:**
Мир начинает думать

---

## Уровень 5 — Архитектура игры

### Системы взаимодействуют

**Механики:**
- Ability system (упрощённый GAS)
- Buffs / debuffs
- Status effects (poison, stun)
- Event-driven gameplay
- Save/Load

**UE5 C++:**
- Delegates
- GameInstanceSubsystem
- Serialization

**Суть:**
Игра — сеть систем

---

## Уровень 6 — Мир как симуляция

### Живой мир

**Механики:**
- Day/Night cycle
- Weather system
- NPC routines
- Factions
- Dynamic events

**UE5 C++:**
- World Subsystem
- Tick optimization
- Data-driven AI

**Суть:**
Мир живёт сам

---

## Уровень 7 — Продвинутый AI

### Интеллект и координация

**Механики:**
- Utility AI
- Squad tactics
- Group coordination
- Adaptive difficulty

**UE5 C++:**
- EQS
- Utility scoring
- Advanced BT services

**Суть:**
AI думает как игрок

---

## Уровень 8 — Мультиплеер

### Сеть

**Механики:**
- Replication
- Client prediction
- Lag compensation
- Matchmaking
- Server authoritative gameplay

**UE5 C++:**
- ReplicatedUsing
- RPC (Server / Client / Multicast)
- NetDriver

**Суть:**
Игра существует в сети

---

## Уровень 9 — AAA Gameplay Systems

### Современный стандарт

**Механики:**
- Combo combat systems
- Animation-driven gameplay
- Motion matching
- Physics interactions
- Large-scale AI

**UE5 C++:**
- Gameplay Ability System (GAS)
- Animation Blueprints
- Root motion

**Суть:**
Каждое действие связано со всем

---

## AAA Уровень — Индустриальный верх

### Масштабные системы

**Механики:**
- World Partition
- Procedural generation
- MMO-scale systems
- Fully data-driven gameplay
- Live service systems
- Telemetry & analytics

**UE5 C++:**
- Engine-level optimization
- Custom subsystems
- Streaming systems
- Task Graph parallelism

**Суть:**
Игра = платформа, а не продукт

---

## Итог

- 0–2: управление и базовые системы  
- 3–4: цикл и AI  
- 5–6: архитектура и симуляция  
- 7–8: интеллект и сеть  
- 9+: AAA масштаб и платформенность
