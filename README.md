
# 😈 Project Diablo Lite

### By_Rafael System

**Motor de rendimiento automático para Android — Automatic Performance Engine**

![Version](https://img.shields.io/badge/Version-v1.0-red?style=flat-square)
![Android](https://img.shields.io/badge/Android-9%2B-green?style=flat-square)
![Root](https://img.shields.io/badge/Root-Magisk%20%7C%20KSU%20%7C%20APatch-blue?style=flat-square)
![Chips](https://img.shields.io/badge/Chips-MTK%20%7C%20SD%20%7C%20Exynos%20%7C%20Tensor%20%7C%20más-purple?style=flat-square)
![License](https://img.shields.io/badge/License-Apache%202.0-orange?style=flat-square)
![Author](https://img.shields.io/badge/Author-By__Rafael__System-red?style=flat-square)

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

Project Diablo Lite es la versión automática del motor de rendimiento Project Diablo. Se instala una vez y trabaja solo: detecta tu chipset, aplica los tweaks correctos y cambia de modo automáticamente según lo que estés haciendo — sin que tengas que tocar nada.

### ✨ Características

- 😈 **DiabloAI** — Motor automático que detecta gaming · balance · idle · carga
- 🔥 **4 modos de rendimiento** — Performance · Balance · Battery · Gaming Pro
- 🎮 **Detección de juegos** — 522 juegos incluidos, lista editable desde la WebUI
- 👆 **Touch optimizado** — 240Hz, latencia mínima, PowerHAL boost
- 🔍 **Detección automática de chipset** — MTK, Snapdragon, Exynos, Tensor, Unisoc, Kirin
- 🌐 **Universal** — Funciona en cualquier dispositivo Android con root
- 🎨 **WebUI** — Interfaz en 5 idiomas con modo manual y AI toggle
- 🔔 **Notificaciones** — Toast al cambiar de modo

### 🧠 Cómo funciona DiabloAI

| Situación detectada | Modo aplicado |
|---|---|
| Juego activo (en gamelist) | 😈 Gaming Pro |
| Pantalla apagada | 🔋 Battery |
| Cargando sin juego | ⚖️ Balance |
| 5 minutos sin actividad | 🔋 Battery |
| Uso normal activo | ⚖️ Balance |
| Juego cerrado | ⚖️ Balance |

> Si DiabloAI está desactivado desde la WebUI, el modo que elegiste se respeta y Diablo no cambia nada automáticamente.

### 😈 Modos disponibles

| Modo | CPU | GPU | Ideal para |
|---|---|---|---|
| 🔥 Performance | Governor máximo | Frecuencia máxima | Rendimiento sostenido |
| ⚖️ Balance | Governor inteligente | Frecuencia media | Uso diario |
| 🔋 Battery | Ahorro agresivo | Frecuencia mínima | Máxima autonomía |
| 😈 Gaming Pro | Máximo | Máximo | Juegos competitivos |

### 🔧 Chipsets soportados

| Chipset | Soporte | Detalles |
|---|---|---|
| MediaTek (MTK) | ✅ Máximo | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` |
| Snapdragon (QCOM) | ✅ Completo | `schedutil` · DCVS bus boost · KGSL GPU |
| Exynos (Samsung) | ✅ Completo | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Completo | Detección via sysfs |
| Unisoc | ✅ Base | Tweaks genéricos CPU/GPU |
| Kirin (Huawei) | ✅ Base | Tweaks genéricos CPU/GPU |

### 📱 Compatibilidad

| Dispositivo | Compatibilidad | Notas |
|---|---|---|
| Xiaomi / Redmi / POCO | ✅ Máxima | Optimizado para HyperOS 2 |
| Samsung | ✅ Parcial | Exynos soportado |
| OnePlus / OPPO | ✅ Parcial | Tweaks genéricos |
| Google Pixel | ✅ Parcial | Tensor soportado |
| Otros Android 9+ | ✅ Base | Tweaks genéricos activos |

### ⚙️ Gestores de root compatibles

| Gestor | Versión mínima | Estado |
|---|---|---|
| Magisk | v20.4+ | ✅ Soportado |
| KernelSU | Cualquiera | ✅ Soportado |
| APatch | Cualquiera | ✅ Soportado |

### 📲 Instalación

1. Descargá el ZIP desde [Releases](../../releases)
2. Abrí Magisk / KSU / APatch
3. Instalá el ZIP
4. Reiniciá el dispositivo
5. Abrí la **WebUI** — Diablo ya está trabajando automáticamente

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
El loop de detección corre cada 4 segundos y es extremadamente liviano — lee archivos de `/proc` que ya están en memoria.

---

## 🇺🇸 English

### What is Project Diablo Lite?

Project Diablo Lite is the automatic version of the Project Diablo performance engine. Install once and it works on its own: detects your chipset, applies the right tweaks, and switches modes automatically based on what you're doing.

### ✨ Features

- 😈 **DiabloAI** — Auto engine detecting gaming · balance · idle · charging
- 🔥 **4 performance modes** — Performance · Balance · Battery · Gaming Pro
- 🎮 **Game detection** — 522 games included, editable list from WebUI
- 👆 **Optimized touch** — 240Hz, minimal latency, PowerHAL boost
- 🔍 **Auto chipset detection** — MTK, Snapdragon, Exynos, Tensor, Unisoc, Kirin
- 🌐 **Universal** — Works on any rooted Android device
- 🎨 **WebUI** — Interface in 5 languages with manual mode and AI toggle
- 🔔 **Notifications** — Toast on mode change

### 🧠 How DiabloAI works

| Detected situation | Applied mode |
|---|---|
| Active game (in gamelist) | 😈 Gaming Pro |
| Screen off | 🔋 Battery |
| Charging without game | ⚖️ Balance |
| 5 minutes idle | 🔋 Battery |
| Normal active use | ⚖️ Balance |
| Game closed | ⚖️ Balance |

> If DiabloAI is turned off from the WebUI, your manually selected mode is respected and Diablo won't change anything automatically.

### 😈 Available modes

| Mode | CPU | GPU | Best for |
|---|---|---|---|
| 🔥 Performance | Max governor | Max frequency | Sustained performance |
| ⚖️ Balance | Smart governor | Mid frequency | Daily use |
| 🔋 Battery | Aggressive saving | Min frequency | Maximum battery life |
| 😈 Gaming Pro | Maximum | Maximum | Competitive gaming |

### 🔧 Supported chipsets

| Chipset | Support | Details |
|---|---|---|
| MediaTek (MTK) | ✅ Maximum | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` |
| Snapdragon (QCOM) | ✅ Full | `schedutil` · DCVS bus boost · KGSL GPU |
| Exynos (Samsung) | ✅ Full | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Full | Detection via sysfs |
| Unisoc | ✅ Base | Generic CPU/GPU tweaks |
| Kirin (Huawei) | ✅ Base | Generic CPU/GPU tweaks |

### 📱 Device compatibility

| Device | Compatibility | Notes |
|---|---|---|
| Xiaomi / Redmi / POCO | ✅ Maximum | Optimized for HyperOS 2 |
| Samsung | ✅ Partial | Exynos supported |
| OnePlus / OPPO | ✅ Partial | Generic tweaks |
| Google Pixel | ✅ Partial | Tensor supported |
| Other Android 9+ | ✅ Base | Generic tweaks active |

### ⚙️ Supported root managers

| Manager | Min version | Status |
|---|---|---|
| Magisk | v20.4+ | ✅ Supported |
| KernelSU | Any | ✅ Supported |
| APatch | Any | ✅ Supported |

### 📲 Installation

1. Download the ZIP from [Releases](../../releases)
2. Open Magisk / KSU / APatch
3. Install the ZIP
4. Reboot your device
5. Open the **WebUI** — Diablo is already working automatically

### ❓ FAQ

**Do I need to configure anything?**
No. On install it detects your chipset and starts working on its own. You can open the WebUI to adjust things, but it's not required.

**What if I want to choose the mode myself?**
Turn off DiabloAI from the toggle in the WebUI. From then on apply the mode you want and Diablo will respect it.

**Can I add my own games to the list?**
Yes. From WebUI → Game list you can search, add and remove packages.

---

## 🇧🇷 Português

### O que é Project Diablo Lite?

Project Diablo Lite é a versão automática do motor de desempenho Project Diablo. Instale uma vez e ele trabalha sozinho: detecta seu chipset, aplica os tweaks corretos e troca de modo automaticamente.

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

1. Baixe o ZIP em [Releases](../../releases)
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
|---|---|
| 🔥 Performance | Performa berkelanjutan |
| ⚖️ Balance | Penggunaan harian |
| 🔋 Battery | Baterai maksimal |
| 😈 Gaming Pro | Game kompetitif |

### 🔧 Chipset didukung

MTK · Snapdragon · Exynos · Tensor · Unisoc · Kirin

### 📲 Instalasi

1. Unduh ZIP dari [Releases](../../releases)
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
|---|---|
| 🔥 Performance | Стабильная производительность |
| ⚖️ Balance | Ежедневное использование |
| 🔋 Battery | Максимальный заряд |
| 😈 Gaming Pro | Соревновательные игры |

### 🔧 Поддерживаемые чипсеты

MTK · Snapdragon · Exynos · Tensor · Unisoc · Kirin

### 📲 Установка

1. Скачайте ZIP из [Releases](../../releases)
2. Откройте Magisk / KSU / APatch
3. Установите из ZIP
4. Перезагрузите
5. Откройте **WebUI** — Diablo уже работает автоматически

---

## 📄 Licencia / License

Apache License 2.0 — By_Rafael System © 2026

---

## 🔗 Links

- 📣 Telegram: [t.me/proyect_diablo](https://t.me/proyect_diablo)
- 🐙 GitHub: [github.com/ByRafaelSystem](https://github.com/ByRafaelSystem)
