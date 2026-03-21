![Project Diablo Lite Banner](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/blob/main/project_diablo_lite_banner.svg?raw=true)

# 😈 Project Diablo Lite

### By_Rafael System

**Motor de rendimiento automático para Android — Automatic Performance Engine**

[![Version](https://img.shields.io/badge/Version-v2.0-red?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
[![Android](https://img.shields.io/badge/Android-9%2B-green?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch)
[![Root](https://img.shields.io/badge/Root-Magisk%20%7C%20KSU%20%7C%20APatch-blue?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch)
[![Chips](https://img.shields.io/badge/Chips-MTK%20%7C%20SD%20%7C%20Exynos%20%7C%20Tensor%20%7C%20m%C3%A1s-purple?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch)
[![License](https://img.shields.io/badge/License-Apache%202.0-orange?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/blob/main/LICENSE)
[![Author](https://img.shields.io/badge/Author-By__Rafael__System-red?style=flat-square)](https://github.com/ByRafaelSystem)

---

## 🌍 Idiomas / Languages

- 🇪🇸 [Español](#español)
- 🇺🇸 [English](#english)
- 🇧🇷 [Português](#português)
- 🇮🇩 [Indonesia](#indonesia)
- 🇷🇺 [Русский](#русский)

---

## 🇪🇸 Español

### ¿Qué es Project Diablo Lite?

Project Diablo Lite es la versión automática del motor de rendimiento Project Diablo. Se instala una vez y trabaja solo: detecta tu chipset automáticamente, aplica los tweaks correctos y cambia de modo según lo que estés haciendo — sin que tengas que tocar nada.

### ✨ Características

- 😈 **DiabloAI v2** — Motor automático con bloqueo por app: detecta gaming · balance · idle · carga · temperatura
- 🔥 **4 modos de rendimiento** — Performance · Balance · Battery · Gaming Pro
- 🎮 **Detección de juegos** — 522 juegos incluidos, lista editable desde la app
- 🔒 **Bloqueo por app** — Al detectar un juego lo bloquea en Gaming Pro hasta que se cierra
- 🧠 **OOM Protect** — Protege el proceso del juego del sistema durante la partida
- 🌡️ **CoolDown inteligente** — Solo actúa en Balance/Battery; Gaming Pro y Performance son libres
- 👆 **Touch Engine** — 240Hz, latencia mínima, PowerHAL boost
- 🌐 **Red gaming** — Buffers TCP optimizados, baja latencia WiFi, RPS en Gaming Pro
- 💾 **VM Tweaks** — RAM optimizada por perfil (swappiness, cache pressure, page cluster)
- 🔍 **Detección automática de chipset** — MTK · SD · Exynos · Tensor · Unisoc · Kirin
- 🔧 **G85 / G99** — Soporte específico para Helio G85 y G99 (PPM + GED)
- ⚡ **Diablo Boost** — Optimización de red para gaming online (TCP Fast Open, power save off)
- 🔋 **FastCharge** — Carga rápida segura configurable
- 🛡️ **Diablo Protect** — Anti-bootloop: desactiva el módulo tras 3 reinicios fallidos
- 🎨 **App propia** — Se administra desde la app **Project Diablo Lite**, interfaz en 5 idiomas con toggle manual y control completo. No requiere KernelSU ni gestor externo para operar.
- 🔔 **Notificaciones** — Alerta al sistema en cada cambio de modo

### 🧠 Cómo funciona DiabloAI v2

| Situación detectada | Modo aplicado |
|---|---|
| Juego activo (en gamelist) | 😈 Gaming Pro — bloqueado hasta cerrar |
| Temperatura alta | 🔋 Battery CoolDown (solo en Balance/Battery) |
| Pantalla apagada | 🔋 Battery |
| Batería baja | 🔋 Battery |
| Cargando sin juego | Modo por defecto |
| Idle (configurable) | 🔋 Battery |
| Uso normal activo | Modo por defecto |
| Juego cerrado | Restaura el perfil previo al juego |

> Si DiabloAI está desactivado, el modo elegido se respeta completamente — Diablo no interviene.
> Las Reglas AI se pueden desactivar por separado para que el AI solo detecte juegos.

### 😈 Modos disponibles

| Modo | CPU | GPU | Red | VM | Ideal para |
|---|---|---|---|---|---|
| 🔥 Performance | Governor máximo | Frecuencia máxima | Normal | Fluido | Rendimiento sostenido |
| ⚖️ Balance | schedutil libre | Ondemand | Normal | Neutro | Uso diario |
| 🔋 Battery | powersave (3 niveles) | Mínima | Normal | Ahorro | Máxima autonomía |
| 😈 Gaming Pro | Máximo | Máximo | Gaming | Gaming | Juegos competitivos |

### 🔧 Chipsets soportados

| Chipset | Soporte | Detalles |
|---|---|---|
| MediaTek (MTK) | ✅ Máximo | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` · G85/G99 |
| Snapdragon (QCOM) | ✅ Completo | `performance` · DCVS · KGSL · Sched boost · Input boost |
| Exynos (Samsung) | ✅ Completo | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Completo | Detección via sysfs |
| Unisoc | ✅ Base | Tweaks genéricos CPU/GPU |
| Kirin (Huawei) | ✅ Base | Tweaks genéricos CPU/GPU |

### 📱 Compatibilidad

| Dispositivo | Compatibilidad | Notas |
|---|---|---|
| Xiaomi / Redmi / POCO | ✅ Máxima | Optimizado para HyperOS 2 |
| Samsung | ✅ Parcial | Exynos soportado |
| OnePlus / OPPO / Realme | ✅ Parcial | Tweaks genéricos |
| Google Pixel | ✅ Parcial | Tensor soportado |
| Otros Android 9+ | ✅ Base | Tweaks genéricos activos |

> ⚠️ **ROMs custom**: Project Diablo está diseñado para ROMs stock y near-stock. En ROMs custom (AOSP, Paranoid, etc.) puede haber conflictos con los tweaks propios de la ROM. Si experimentás problemas de touch o input, desactivá el **Touch Engine** desde la app.

### ⚙️ Gestores de root compatibles

| Gestor | Versión mínima | Estado |
|---|---|---|
| Magisk | v20.4+ | ✅ Soportado |
| KernelSU | Cualquiera | ✅ Soportado |
| APatch | Cualquiera | ✅ Soportado |

### 📲 Instalación

1. Descargá el ZIP desde [Releases](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
2. Abrí Magisk / KSU / APatch
3. Instalá el módulo desde el ZIP
4. Reiniciá el dispositivo
5. Abrí la **app Project Diablo Lite** — DiabloAI ya está activo automáticamente

### ❓ Preguntas frecuentes

**¿Necesito configurar algo?**
No. Al instalar detecta tu chipset y empieza a funcionar solo con DiabloAI activo.

**¿Qué pasa si quiero elegir el modo yo?**
Desactivá DiabloAI desde el toggle en la app. El modo que aplicás se respeta hasta que lo cambies.

**¿Puedo agregar mis propios juegos?**
Sí. Desde la app → Lista de juegos podés buscar, agregar y eliminar paquetes.

**¿Es compatible con Project Diablo Pro?**
Son módulos separados del mismo autor. No instalar ambos al mismo tiempo.

**¿Consume batería en segundo plano?**
El motor de detección es extremadamente liviano — lee `/proc` que ya está en memoria caché del kernel.

**¿Por qué no funciona bien en mi ROM custom?**
Las ROMs custom tienen sus propios tweaks de kernel e input que pueden competir con los de Diablo. Desactivá el Touch Engine desde la app para resolver conflictos de touch/aim.

---

## 🇺🇸 English

### What is Project Diablo Lite?

Project Diablo Lite is the automatic version of the Project Diablo performance engine. Install once and it works on its own: auto-detects your chipset, applies the right tweaks, and switches modes based on what you're doing.

### ✨ Features

- 😈 **DiabloAI v2** — Auto engine with per-app lock: detects gaming · balance · idle · charging · temperature
- 🔥 **4 performance modes** — Performance · Balance · Battery · Gaming Pro
- 🎮 **Game detection** — 522 games included, editable list from the app
- 🔒 **App lock** — Locks Gaming Pro while a game is active, restores your previous profile when it closes
- 🧠 **OOM Protect** — Shields game process from being killed by Android during play
- 🌡️ **Smart CoolDown** — Only acts in Balance/Battery; Gaming Pro and Performance run free
- 👆 **Touch Engine** — 240Hz, minimal latency, PowerHAL boost
- 🌐 **Net Gaming** — TCP buffers, low-latency WiFi, RPS in Gaming Pro
- 💾 **VM Tweaks** — RAM tuned per profile (swappiness, cache pressure, page cluster)
- 🔍 **Auto chipset detection** — MTK · SD · Exynos · Tensor · Unisoc · Kirin
- 🔧 **G85 / G99** — Specific support for Helio G85 and G99 (PPM + GED)
- ⚡ **Diablo Boost** — Network optimization for online gaming
- 🔋 **FastCharge** — Safe configurable fast charging
- 🛡️ **Diablo Protect** — Anti-bootloop: disables module after 3 failed boots
- 🎨 **Dedicated app** — Managed from the **Project Diablo Lite app**, interface in 5 languages with manual mode and full control. No KernelSU or external manager needed to operate.
- 🔔 **Notifications** — System alert on every mode change

### 🧠 How DiabloAI v2 works

| Detected situation | Applied mode |
|---|---|
| Active game (in gamelist) | 😈 Gaming Pro — locked until closed |
| High temperature | 🔋 Battery CoolDown (Balance/Battery only) |
| Screen off | 🔋 Battery |
| Low battery | 🔋 Battery |
| Charging without game | Default mode |
| Idle (configurable) | 🔋 Battery |
| Normal active use | Default mode |
| Game closed | Restores profile from before the game |

> If DiabloAI is turned off, your manually selected mode is fully respected.
> AI Rules can be disabled separately so the AI only handles game detection.

### 😈 Available modes

| Mode | CPU | GPU | Network | VM | Best for |
|---|---|---|---|---|---|
| 🔥 Performance | Max governor | Max frequency | Normal | Smooth | Sustained performance |
| ⚖️ Balance | Free schedutil | Ondemand | Normal | Neutral | Daily use |
| 🔋 Battery | powersave (3 levels) | Minimum | Normal | Save | Maximum battery life |
| 😈 Gaming Pro | Maximum | Maximum | Gaming | Gaming | Competitive gaming |

### 🔧 Supported chipsets

| Chipset | Support | Details |
|---|---|---|
| MediaTek (MTK) | ✅ Maximum | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` · G85/G99 |
| Snapdragon (QCOM) | ✅ Full | `performance` · DCVS · KGSL · Sched boost · Input boost |
| Exynos (Samsung) | ✅ Full | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Full | Detection via sysfs |
| Unisoc | ✅ Base | Generic CPU/GPU tweaks |
| Kirin (Huawei) | ✅ Base | Generic CPU/GPU tweaks |

### 📱 Device compatibility

| Device | Compatibility | Notes |
|---|---|---|
| Xiaomi / Redmi / POCO | ✅ Maximum | Optimized for HyperOS 2 |
| Samsung | ✅ Partial | Exynos supported |
| OnePlus / OPPO / Realme | ✅ Partial | Generic tweaks |
| Google Pixel | ✅ Partial | Tensor supported |
| Other Android 9+ | ✅ Base | Generic tweaks active |

> ⚠️ **Custom ROMs**: Project Diablo is designed for stock and near-stock ROMs. On custom ROMs (AOSP, Paranoid, etc.) there may be conflicts with the ROM's own tweaks. If you experience touch or aim issues, disable the **Touch Engine** in the app.

### ⚙️ Supported root managers

| Manager | Min version | Status |
|---|---|---|
| Magisk | v20.4+ | ✅ Supported |
| KernelSU | Any | ✅ Supported |
| APatch | Any | ✅ Supported |

### 📲 Installation

1. Download the ZIP from [Releases](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
2. Open Magisk / KSU / APatch
3. Install the module from the ZIP
4. Reboot your device
5. Open the **Project Diablo Lite app** — DiabloAI is already running automatically

### ❓ FAQ

**Do I need to configure anything?**
No. On install it detects your chipset and starts working automatically with DiabloAI active.

**What if I want to choose the mode myself?**
Turn off DiabloAI from the toggle in the app. Your selected mode is respected until you change it.

**Can I add my own games to the list?**
Yes. From the app → Game list you can search, add and remove packages.

**Is it compatible with Project Diablo Pro?**
They are separate modules by the same author. Do not install both at the same time.

**Why doesn't it work well on my custom ROM?**
Custom ROMs have their own kernel and input tweaks that can conflict with Diablo's. Disable the Touch Engine in the app to resolve touch/aim conflicts.

---

## 🇧🇷 Português

### O que é Project Diablo Lite?

Project Diablo Lite é a versão automática do motor de desempenho Project Diablo. Instale uma vez e ele trabalha sozinho: detecta seu chipset automaticamente, aplica os tweaks corretos e troca de modo com base no que você está fazendo.

### ✨ Recursos

- 😈 **DiabloAI v2** — Motor automático com bloqueio por app
- 🔥 **4 modos** — Performance · Balance · Battery · Gaming Pro
- 🎮 **Detecção de jogos** — 522 jogos incluídos, lista editável pelo app
- 🔒 **Bloqueio por app** — Gaming Pro ativo enquanto o jogo roda
- 🌡️ **CoolDown inteligente** — Só atua em Balance/Battery
- 💾 **VM Tweaks** — RAM otimizada por perfil
- 🌐 **Net Gaming** — Rede otimizada no Gaming Pro
- 🛡️ **Diablo Protect** — Anti-bootloop integrado

### 😈 Modos disponíveis

| Modo | Ideal para |
|---|---|
| 🔥 Performance | Desempenho sustentado |
| ⚖️ Balance | Uso diário |
| 🔋 Battery | Máxima autonomia |
| 😈 Gaming Pro | Jogos competitivos |

### 🔧 Chipsets suportados

MTK · Snapdragon · Exynos · Tensor · Unisoc · Kirin

### 📲 Instalação

1. Baixe o ZIP em [Releases](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
2. Abra o Magisk / KSU / APatch
3. Instale pelo ZIP
4. Reinicie
5. Abra o **app Project Diablo Lite** — DiabloAI já está funcionando

---

## 🇮🇩 Indonesia

### Apa itu Project Diablo Lite?

Project Diablo Lite adalah versi otomatis dari mesin performa Project Diablo. Instal sekali dan bekerja sendiri: mendeteksi chipset secara otomatis, menerapkan tweak yang tepat, dan berganti mode berdasarkan aktivitas Anda.

### ✨ Fitur

- 😈 **DiabloAI v2** — Mesin otomatis dengan kunci per-app
- 🔥 **4 mode** — Performance · Balance · Battery · Gaming Pro
- 🎮 **Deteksi game** — 522 game, daftar bisa diedit
- 🔒 **Kunci app** — Gaming Pro aktif selama game berjalan
- 🌡️ **CoolDown cerdas** — Hanya aktif di Balance/Battery
- 💾 **VM Tweaks** — RAM dioptimalkan per profil
- 🌐 **Net Gaming** — Jaringan dioptimalkan di Gaming Pro
- 🛡️ **Diablo Protect** — Anti-bootloop terintegrasi

### 😈 Mode tersedia

| Mode | Terbaik untuk |
|---|---|
| 🔥 Performance | Performa berkelanjutan |
| ⚖️ Balance | Penggunaan harian |
| 🔋 Battery | Baterai maksimal |
| 😈 Gaming Pro | Game kompetitif |

### 🔧 Chipset didukung

MTK · Snapdragon · Exynos · Tensor · Unisoc · Kirin

### 📲 Instalasi

1. Unduh ZIP dari [Releases](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
2. Buka Magisk / KSU / APatch
3. Pasang dari ZIP
4. Reboot
5. Buka **app Project Diablo Lite** — DiabloAI sudah aktif otomatis

---

## 🇷🇺 Русский

### Что такое Project Diablo Lite?

Project Diablo Lite — автоматическая версия движка производительности Project Diablo. Установите один раз: автоматически определяет чипсет, применяет нужные твики и переключает режимы в зависимости от того, что вы делаете.

### ✨ Возможности

- 😈 **DiabloAI v2** — Автоматический движок с блокировкой по приложению
- 🔥 **4 режима** — Performance · Balance · Battery · Gaming Pro
- 🎮 **Определение игр** — 522 игры, список редактируется
- 🔒 **Блокировка по app** — Gaming Pro активен пока игра запущена
- 🌡️ **Умный CoolDown** — Только в Balance/Battery
- 💾 **VM Tweaks** — RAM оптимизирована под каждый профиль
- 🌐 **Net Gaming** — Сеть оптимизирована в Gaming Pro
- 🛡️ **Diablo Protect** — Защита от bootloop

### 😈 Доступные режимы

| Режим | Лучше всего для |
|---|---|
| 🔥 Performance | Стабильная производительность |
| ⚖️ Balance | Ежедневное использование |
| 🔋 Battery | Максимальный заряд |
| 😈 Gaming Pro | Соревновательные игры |

### 🔧 Поддерживаемые чипсеты

MTK · Snapdragon · Exynos · Tensor · Unisoc · Kirin

### 📲 Установка

1. Скачайте ZIP из [Releases](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
2. Откройте Magisk / KSU / APatch
3. Установите из ZIP
4. Перезагрузите
5. Откройте **app Project Diablo Lite** — DiabloAI уже работает автоматически

---

## 📄 Licencia / License

Apache License 2.0 — By_Rafael System © 2026

---

## 🔗 Links

- 📣 Telegram: [t.me/proyect_diablo](https://t.me/proyect_diablo)
- 🐙 GitHub: [github.com/ByRafaelSystem](https://github.com/ByRafaelSystem)
