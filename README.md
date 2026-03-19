![Project Diablo Lite Banner](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/blob/main/project_diablo_lite_banner.svg?raw=true)

# 😈 Project Diablo Lite

### By\_Rafael System

**Motor de rendimiento automático para Android — Automatic Performance Engine**

[![Version](https://img.shields.io/badge/Version-v2.0.5-red?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
[![Android](https://img.shields.io/badge/Android-9%2B-green?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch)
[![Root](https://img.shields.io/badge/Root-Magisk%20%7C%20KSU%20%7C%20APatch-blue?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch)
[![Chips](https://img.shields.io/badge/Chips-MTK%20%7C%20SD%20%7C%20Exynos%20%7C%20Tensor%20%7C%20m%C3%A1s-purple?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch)
[![License](https://img.shields.io/badge/License-Apache%202.0-orange?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/blob/main/LICENSE)
[![Author](https://img.shields.io/badge/Author-By__Rafael__System-red?style=flat-square)](https://github.com/ByRafaelSystem)

---

## 🌍 Idiomas / Languages

* 🇪🇸 [Español](#español)
* 🇺🇸 [English](#english)
* 🇧🇷 [Português](#português)
* 🇮🇩 [Indonesia](#indonesia)
* 🇷🇺 [Русский](#русский)

---

## 🇪🇸 Español

### ¿Qué es Project Diablo Lite?

Project Diablo Lite es la versión automática del motor de rendimiento Project Diablo. Se instala una vez y trabaja solo: detecta tu chipset, aplica los tweaks correctos y cambia de modo automáticamente según lo que estés haciendo — sin que tengas que tocar nada.

### ✨ Características

* 😈 **DiabloAI** — Motor automático que detecta gaming · balance · idle · carga
* 🔥 **4 modos de rendimiento** — Performance · Balance · Battery · Gaming Pro
* 🎮 **Detección de juegos** — 522 juegos incluidos, lista editable desde la WebUI
* 👆 **Touch optimizado** — 240Hz, latencia mínima, PowerHAL boost
* 🔍 **Detección automática de chipset** — MTK, Snapdragon, Exynos, Tensor, Unisoc, Kirin
* 🌐 **Universal** — Funciona en cualquier dispositivo Android con root
* 🎨 **WebUI** — Interfaz en 5 idiomas con modo manual y AI toggle
* 🔔 **Notificaciones** — Toast al cambiar de modo
* 🌐 **Diablo Boost** — Optimización de buffers TCP/UDP y desactivación de WiFi power save para gaming online
* ⚡ **FastCharge** — Aumenta la corriente de carga (configurable desde la WebUI)
* 🛡️ **Diablo Protect** — Protección anti-bootloop: desactiva el módulo automáticamente tras 3 fallos de boot consecutivos
* 🖥️ **AmeRender** — Motor de render avanzado: optimiza SurfaceFlinger, shaders, GPU y cgroup de tareas
* 📺 **Zeta** — Fija el refresh rate al máximo del panel en cada arranque
* ⚙️ **QCOM Scheduler** — Tweaks avanzados de scheduler, input boost y schedtune para Snapdragon
* 💾 **DVFSRC** — Control de ancho de banda de memoria DDR (solo MediaTek)
* 🎯 **FPSGO** — Motor de control de FPS del kernel MediaTek integrado por modo

### 🧠 Cómo funciona DiabloAI

| Situación detectada | Modo aplicado |
| --- | --- |
| Juego activo (en gamelist) | 😈 Gaming Pro |
| Pantalla apagada | 🔋 Battery |
| Cargando sin juego | ⚖️ Balance |
| 5 minutos sin actividad | 🔋 Battery |
| Uso normal activo | ⚖️ Balance |
| Juego cerrado | ⚖️ Balance |

> Si DiabloAI está desactivado desde la WebUI, el modo que elegiste se respeta y Diablo no cambia nada automáticamente.

### 😈 Modos disponibles

| Modo | CPU | GPU | Ideal para |
| --- | --- | --- | --- |
| 🔥 Performance | Governor máximo | Frecuencia máxima | Rendimiento sostenido |
| ⚖️ Balance | Governor inteligente | Frecuencia media | Uso diario |
| 🔋 Battery | Ahorro agresivo | Frecuencia mínima | Máxima autonomía |
| 😈 Gaming Pro | Máximo | Máximo + animaciones 0 | Juegos competitivos |

### 🔧 Chipsets soportados

| Chipset | Soporte | Detalles |
| --- | --- | --- |
| MediaTek (MTK) | ✅ Máximo | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` · GED boost · Mali |
| Snapdragon (QCOM) | ✅ Completo | `schedutil` · DCVS bus boost · KGSL GPU · input_boost · schedtune |
| Exynos (Samsung) | ✅ Completo | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Completo | Detección via sysfs |
| Unisoc | ✅ Base | Tweaks genéricos CPU/GPU |
| Kirin (Huawei) | ✅ Base | Tweaks genéricos CPU/GPU |

### 📱 Compatibilidad

| Dispositivo | Compatibilidad | Notas |
| --- | --- | --- |
| Xiaomi / Redmi / POCO | ✅ Máxima | Optimizado para HyperOS 2 |
| Samsung | ✅ Parcial | Exynos soportado |
| OnePlus / OPPO | ✅ Parcial | Tweaks genéricos + touch panel OPPO/OnePlus |
| Google Pixel | ✅ Parcial | Tensor soportado |
| Otros Android 9+ | ✅ Base | Tweaks genéricos activos |

### ⚙️ Gestores de root compatibles

| Gestor | Versión mínima | Estado |
| --- | --- | --- |
| Magisk | v20.4+ | ✅ Soportado |
| KernelSU | Cualquiera | ✅ Soportado |
| APatch | Cualquiera | ✅ Soportado |

### 📲 Instalación

1. Descargá el ZIP desde [Releases](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
2. Abrí Magisk / KSU / APatch
3. Instalá el ZIP
4. Reiniciá el dispositivo
5. Abrí la **WebUI** — Diablo ya está trabajando automáticamente

### 🆕 Novedades v2.0.5

* **Diablo Boost** — Optimización completa de red (buffers TCP/UDP 4 MB, tcp_fastopen, low latency, WiFi power save off). Activable desde la WebUI sin reinicio.
* **FastCharge** — Carga rápida configurable (por defecto 2000 mA). Detecta automáticamente los nodos USB y battery del dispositivo. Temperatura de corte configurable.
* **Diablo Protect** — Sistema anti-bootloop. Detecta 3 arranques incompletos consecutivos y desactiva el módulo automáticamente. El contador se resetea cuando el boot completa exitosamente. Avisa al usuario con notificación.
* **AmeRender (actualizado)** — Motor de render unificado en un solo script. Incluye: Diablo Render Engine (SurfaceFlinger adaptativo por VSYNC), Diablo Render FlowX (GPU MTK/Adreno/Mali/PowerVR + cgroup de tareas), y Diablo Render Plus / Facur (phase offsets dinámicos por FPS detectado). Corre una sola vez al boot en background.
* **Zeta** — Nuevo script dedicado a fijar el refresh rate al máximo del panel. Usa `cmd display dump` para detectar el FPS real y lo aplica vía `settings` + `resetprop`.
* **QCOM Scheduler (nuevo)** — Tres funciones dedicadas para Snapdragon: `qcom_sched_gaming` (latencia mínima, input_boost 200ms, schedtune.boost 5), `qcom_sched_balance` y `qcom_sched_save`. Se integran al flujo de `apply_mode`.
* **DVFSRC mejorado** — Ahora `dvfsrc_balance` usa `kakangkuh` (sin bloquear el nodo) para permitir que el sistema retome el control del DDR en modo normal.
* **FPSGO por modo** — Gaming Pro y Performance activan `fpsgo_gaming` (sin throttle térmico, boost libre). Balance y Battery llaman a `fpsgo_normal`.
* **Detección de juegos reforzada** — Usa `dd + tr '\0' '\n'` para leer `/proc/PID/cmdline`, filtrado por `oom_score_adj < 900` y validación de formato de package con regex. Más robusto en kernels strict de Android.
* **DiabloAI mejorado** — Detecta la transición AI OFF→ON y fuerza reevaluación completa. `PREV_AI_STATE` evita reevaluar en cada ciclo cuando el estado no cambió.
* **Trigger FastCharge desde WebUI** — Nuevo archivo `fc_trigger` que el loop principal detecta y aplica o restaura la corriente de carga sin reinicio.
* **Log de AI** — Diablo escribe un log de debug (`diablo.log.ai`) con screen/charging/game en cada ciclo para facilitar el diagnóstico.
* **Gamelist** — 522 juegos incluidos por defecto.

### ❓ Preguntas frecuentes

**¿Necesito configurar algo?**
No. Al instalar detecta tu chipset y empieza a funcionar solo. Podés abrir la WebUI para ajustar o cambiar algo, pero no es necesario.

**¿Qué pasa si quiero elegir el modo yo?**
Desactivá DiabloAI desde el toggle en la WebUI. A partir de ahí aplicá el modo que quieras y Diablo lo respeta.

**¿Puedo agregar mis propios juegos a la lista?**
Sí. Desde la WebUI → Lista de juegos podés buscar, agregar y eliminar paquetes.

**¿Es compatible con Project Diablo y ARG?**
Son módulos separados del mismo autor. No instalar ambos Diablo al mismo tiempo.

**¿Consume batería en segundo plano?**
El loop de DiabloAI corre cada 4 segundos y es extremadamente liviano — lee archivos de `/proc` que ya están en memoria.

**¿Qué pasa si el módulo causó un bootloop?**
Diablo Protect lo detecta y desactiva el módulo automáticamente tras 3 fallos consecutivos. Al siguiente boot recibirás una notificación explicando qué pasó. Podés desinstalar el módulo desde tu gestor de root.

**¿Diablo Boost puede afectar la estabilidad de la conexión?**
No. Solo optimiza los buffers del kernel y desactiva el power save del WiFi. No modifica rutas ni DNS. Si notás algo raro, desactivalo desde la WebUI.

---

## 🇺🇸 English

### What is Project Diablo Lite?

Project Diablo Lite is the automatic version of the Project Diablo performance engine. Install once and it works on its own: detects your chipset, applies the right tweaks, and switches modes automatically based on what you're doing.

### ✨ Features

* 😈 **DiabloAI** — Auto engine detecting gaming · balance · idle · charging
* 🔥 **4 performance modes** — Performance · Balance · Battery · Gaming Pro
* 🎮 **Game detection** — 522 games included, editable list from WebUI
* 👆 **Optimized touch** — 240Hz, minimal latency, PowerHAL boost
* 🔍 **Auto chipset detection** — MTK, Snapdragon, Exynos, Tensor, Unisoc, Kirin
* 🌐 **Universal** — Works on any rooted Android device
* 🎨 **WebUI** — Interface in 5 languages with manual mode and AI toggle
* 🔔 **Notifications** — Toast on mode change
* 🌐 **Diablo Boost** — TCP/UDP buffer optimization and WiFi power save off for online gaming
* ⚡ **FastCharge** — Configurable charging current boost (WebUI)
* 🛡️ **Diablo Protect** — Anti-bootloop: auto-disables the module after 3 consecutive failed boots
* 🖥️ **AmeRender** — Advanced render engine: SurfaceFlinger, shaders, GPU and task cgroup
* 📺 **Zeta** — Locks refresh rate to the panel's maximum on every boot
* ⚙️ **QCOM Scheduler** — Advanced scheduler, input boost and schedtune tweaks for Snapdragon
* 💾 **DVFSRC** — DDR memory bandwidth control (MediaTek only)
* 🎯 **FPSGO** — MediaTek kernel FPS engine integrated per mode

### 🧠 How DiabloAI works

| Detected situation | Applied mode |
| --- | --- |
| Active game (in gamelist) | 😈 Gaming Pro |
| Screen off | 🔋 Battery |
| Charging without game | ⚖️ Balance |
| 5 minutes idle | 🔋 Battery |
| Normal active use | ⚖️ Balance |
| Game closed | ⚖️ Balance |

> If DiabloAI is turned off from the WebUI, your manually selected mode is respected and Diablo won't change anything automatically.

### 😈 Available modes

| Mode | CPU | GPU | Best for |
| --- | --- | --- | --- |
| 🔥 Performance | Max governor | Max frequency | Sustained performance |
| ⚖️ Balance | Smart governor | Mid frequency | Daily use |
| 🔋 Battery | Aggressive saving | Min frequency | Maximum battery life |
| 😈 Gaming Pro | Maximum | Maximum + 0ms animations | Competitive gaming |

### 🔧 Supported chipsets

| Chipset | Support | Details |
| --- | --- | --- |
| MediaTek (MTK) | ✅ Maximum | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` · GED boost · Mali |
| Snapdragon (QCOM) | ✅ Full | `schedutil` · DCVS bus boost · KGSL GPU · input_boost · schedtune |
| Exynos (Samsung) | ✅ Full | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Full | Detection via sysfs |
| Unisoc | ✅ Base | Generic CPU/GPU tweaks |
| Kirin (Huawei) | ✅ Base | Generic CPU/GPU tweaks |

### 📱 Device compatibility

| Device | Compatibility | Notes |
| --- | --- | --- |
| Xiaomi / Redmi / POCO | ✅ Maximum | Optimized for HyperOS 2 |
| Samsung | ✅ Partial | Exynos supported |
| OnePlus / OPPO | ✅ Partial | Generic tweaks + OPPO/OnePlus touch panel |
| Google Pixel | ✅ Partial | Tensor supported |
| Other Android 9+ | ✅ Base | Generic tweaks active |

### ⚙️ Supported root managers

| Manager | Min version | Status |
| --- | --- | --- |
| Magisk | v20.4+ | ✅ Supported |
| KernelSU | Any | ✅ Supported |
| APatch | Any | ✅ Supported |

### 📲 Installation

1. Download the ZIP from [Releases](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
2. Open Magisk / KSU / APatch
3. Install the ZIP
4. Reboot your device
5. Open the **WebUI** — Diablo is already working automatically

### 🆕 What's new in v2.0.5

* **Diablo Boost** — Network optimization (4 MB TCP/UDP buffers, tcp_fastopen, low latency, WiFi power save off). Toggle from WebUI without reboot.
* **FastCharge** — Configurable fast charging (default 2000 mA). Auto-detects USB and battery nodes. Cut-off temperature configurable.
* **Diablo Protect** — Anti-bootloop system. Detects 3 consecutive incomplete boots and auto-disables the module. Counter resets on successful boot. Notifies the user.
* **AmeRender (updated)** — Unified render engine: Diablo Render Engine (adaptive SurfaceFlinger by VSYNC), Diablo Render FlowX (GPU MTK/Adreno/Mali/PowerVR + task cgroup), Diablo Render Plus / Facur (dynamic phase offsets by detected FPS). Runs once at boot in background.
* **Zeta** — New script dedicated to locking refresh rate to the panel maximum. Detects real FPS via `cmd display dump`.
* **QCOM Scheduler (new)** — Dedicated functions for Snapdragon: gaming (minimum latency, input_boost 200ms, schedtune.boost 5), balance and save. Integrated into `apply_mode`.
* **Improved DVFSRC** — `dvfsrc_balance` now uses `kakangkuh` (no lock) to let the system regain DDR control in normal mode.
* **FPSGO per mode** — Gaming Pro and Performance enable `fpsgo_gaming` (no thermal throttle, free boost). Balance and Battery call `fpsgo_normal`.
* **Reinforced game detection** — Uses `dd + tr '\0' '\n'` to read `/proc/PID/cmdline`, filtered by `oom_score_adj < 900` and package format regex. More robust on strict Android kernels.
* **Improved DiabloAI** — Detects AI OFF→ON transition and forces full re-evaluation. `PREV_AI_STATE` avoids redundant checks each cycle.
* **FastCharge trigger from WebUI** — New `fc_trigger` file detected by the main loop, applies or restores charging current without reboot.
* **AI log** — Diablo writes a debug log (`diablo.log.ai`) with screen/charging/game on each cycle.
* **Gamelist** — 522 games included by default.

### ❓ FAQ

**Do I need to configure anything?**
No. On install it detects your chipset and starts working on its own. You can open the WebUI to adjust things, but it's not required.

**What if I want to choose the mode myself?**
Turn off DiabloAI from the toggle in the WebUI. From then on apply the mode you want and Diablo will respect it.

**Can I add my own games to the list?**
Yes. From WebUI → Game list you can search, add and remove packages.

**What if the module caused a bootloop?**
Diablo Protect detects it and auto-disables the module after 3 consecutive failures. On the next boot you'll receive a notification. You can uninstall from your root manager.

**Does Diablo Boost affect connection stability?**
No. It only optimizes kernel buffers and disables WiFi power save. Routes and DNS are untouched. If you notice anything odd, disable it from the WebUI.

---

## 🇧🇷 Português

### O que é Project Diablo Lite?

Project Diablo Lite é a versão automática do motor de desempenho Project Diablo. Instale uma vez e ele trabalha sozinho: detecta seu chipset, aplica os tweaks corretos e troca de modo automaticamente.

### 😈 Modos disponíveis

| Modo | Ideal para |
| --- | --- |
| 🔥 Performance | Desempenho sustentado |
| ⚖️ Balance | Uso diário |
| 🔋 Battery | Máxima autonomia |
| 😈 Gaming Pro | Jogos competitivos |

### 🆕 Novidades v2.0.5

* **Diablo Boost** — Otimização de rede TCP/UDP e WiFi power save off para gaming online
* **FastCharge** — Corrente de carregamento configurável via WebUI
* **Diablo Protect** — Proteção anti-bootloop: desativa o módulo após 3 falhas consecutivas
* **AmeRender atualizado** — Motor de render unificado (SurfaceFlinger, GPU, cgroup)
* **Zeta** — Trava o refresh rate no máximo do painel
* **QCOM Scheduler** — Tweaks avançados para Snapdragon (input_boost, schedtune)
* **Detecção de jogos reforçada** — Leitura robusta de `/proc/PID/cmdline`
* **522 jogos** na gamelist padrão

### 🔧 Chipsets suportados

MTK · Snapdragon · Exynos · Tensor · Unisoc · Kirin

### 📲 Instalação

1. Baixe o ZIP em [Releases](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
2. Abra o Magisk / KSU / APatch
3. Instale pelo ZIP
4. Reinicie
5. Abra o **WebUI** — Diablo já está funcionando automaticamente

---

## 🇮🇩 Indonesia

### Apa itu Project Diablo Lite?

Project Diablo Lite adalah versi otomatis dari mesin performa Project Diablo. Instal sekali dan bekerja sendiri: mendeteksi chipset, menerapkan tweak yang tepat, dan berganti mode secara otomatis.

### 😈 Mode tersedia

| Mode | Terbaik untuk |
| --- | --- |
| 🔥 Performance | Performa berkelanjutan |
| ⚖️ Balance | Penggunaan harian |
| 🔋 Battery | Baterai maksimal |
| 😈 Gaming Pro | Game kompetitif |

### 🆕 Yang baru di v2.0.5

* **Diablo Boost** — Optimasi buffer TCP/UDP dan WiFi power save off untuk gaming online
* **FastCharge** — Arus pengisian yang dapat dikonfigurasi melalui WebUI
* **Diablo Protect** — Anti-bootloop: menonaktifkan modul setelah 3 kegagalan boot berturut-turut
* **AmeRender diperbarui** — Mesin render terpadu (SurfaceFlinger, GPU, cgroup)
* **Zeta** — Mengunci refresh rate ke maksimum panel
* **QCOM Scheduler** — Tweak lanjutan untuk Snapdragon (input_boost, schedtune)
* **Deteksi game diperkuat** — Pembacaan `/proc/PID/cmdline` yang lebih robust
* **522 game** dalam daftar default

### 🔧 Chipset didukung

MTK · Snapdragon · Exynos · Tensor · Unisoc · Kirin

### 📲 Instalasi

1. Unduh ZIP dari [Releases](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
2. Buka Magisk / KSU / APatch
3. Pasang dari ZIP
4. Reboot
5. Buka **WebUI** — Diablo sudah bekerja otomatis

---

## 🇷🇺 Русский

### Что такое Project Diablo Lite?

Project Diablo Lite — автоматическая версия движка производительности Project Diablo. Установите один раз и он работает сам: определяет чипсет, применяет нужные твики и автоматически переключает режимы.

### 😈 Доступные режимы

| Режим | Лучше всего для |
| --- | --- |
| 🔥 Performance | Стабильная производительность |
| ⚖️ Balance | Ежедневное использование |
| 🔋 Battery | Максимальный заряд |
| 😈 Gaming Pro | Соревновательные игры |

### 🆕 Что нового в v2.0.5

* **Diablo Boost** — Оптимизация буферов TCP/UDP и отключение WiFi power save для онлайн-игр
* **FastCharge** — Настраиваемый ток зарядки через WebUI
* **Diablo Protect** — Защита от bootloop: отключает модуль после 3 неудачных загрузок подряд
* **AmeRender обновлён** — Единый движок рендеринга (SurfaceFlinger, GPU, cgroup)
* **Zeta** — Фиксирует частоту обновления на максимуме экрана
* **QCOM Scheduler** — Расширенные твики для Snapdragon (input_boost, schedtune)
* **Улучшенное обнаружение игр** — Более надёжное чтение `/proc/PID/cmdline`
* **522 игры** в списке по умолчанию

### 🔧 Поддерживаемые чипсеты

MTK · Snapdragon · Exynos · Tensor · Unisoc · Kirin

### 📲 Установка

1. Скачайте ZIP из [Releases](https://github.com/ByRafaelSystem/Project-Diablo-Lite-magisk-ksu-apatch/releases)
2. Откройте Magisk / KSU / APatch
3. Установите из ZIP
4. Перезагрузите
5. Откройте **WebUI** — Diablo уже работает автоматически

---

## 📄 Licencia / License

Apache License 2.0 — By\_Rafael System © 2026

---

## 🔗 Links

* 📣 Telegram: [t.me/proyect\_diablo](https://t.me/proyect_diablo)
* 🐙 GitHub: [github.com/ByRafaelSystem](https://github.com/ByRafaelSystem)
