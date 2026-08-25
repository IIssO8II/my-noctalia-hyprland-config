# 🌙 Noctalia + Hyprland Dotfiles

Configuración personalizada de atajos de teclado (`binds.lua`) integrados con **Noctalia Shell** para Hyprland. Diseñada para ser rápida, limpia e intuitiva mediante nemotecnia.

Requiere: Noctalia Shell, Hyprland, Hyprfm, Vscodium, gSlapper, Whatsie, VacuumTube, Firefox, Kitty

---

## 🎹 Guía de Atajos de Teclado (Keybinds)

> **Nota:** `SUPER` hace referencia a la tecla Windows

### 🪟 Gestión de Ventanas

| Atajo | Acción |
| :--- | :--- |
| `SUPER + Escape` | Forzar cierre de proceso (`hyprctl kill`) |
| `SUPER + Q` | Cerrar ventana activa |
| `SUPER + ALT + Espacio` | Alternar modo flotante / mosaico |
| `SUPER + D` | Pantalla completa con márgenes (dwindle mode 1) |
| `SUPER + F11` | Pantalla completa real |
| `SUPER + J` | Cambiar orientación de división (*togglesplit*) |
| `SUPER + Flechas` | Mover el foco entre ventanas (Izquierda, Derecha, Arriba, Abajo) |
| `ALT + Tab` | Pasar a la siguiente ventana en el workspace |
| `SUPER + Tab` | Abrir el conmutador visual de ventanas de Noctalia |
| `SUPER + SHIFT + Flechas` | Mover posición de la ventana activa |
| `SUPER + Clic Izquierdo` | Arrastrar ventana flotante |
| `SUPER + Clic Derecho` | Redimensionar ventana flotante |
| `SUPER + +` / `SUPER + -` | Zoom de pantalla (Aumentar / Reducir) |
| `SUPER + Numpad 82 / 86` | Zoom de pantalla con teclado numérico |

---

### 🚀 Lanzador de Aplicaciones (Nemotecnia)

| Atajo | Tecla | Aplicación |
| :--- | :---: | :--- |
| `SUPER + Enter` | **Enter** | Terminal predeterminada (`TERMINAL`) |
| `SUPER + F` | **F** | **F**irefox |
| `SUPER + E` | **E** | **E**xplorer / Gestor de Archivos (`FILE_MANAGER`) |
| `SUPER + O` | **O** | **O**pen Code (VSCodium - Flatpak) |
| `SUPER + Y` | **Y** | **Y**ouTube / Vacuumtube (Flatpak) |
| `SUPER + M` | **M** | **M**essaging / Whatsie (Flatpak) |
| `SUPER + C` | **C** | **C**alculadora |
| `CTRL + SHIFT + Escape` | — | Monitor de sistema (`btop`) |

---

### 🖥️ Noctalia Shell

| Atajo | Acción |
| :--- | :--- |
| `SUPER + Espacio` | Menú / Lanzador de aplicaciones principal |
| `SUPER + W` | **W**allpapers (Buscador de Wallhaven en Noctalia) |
| `SUPER + SHIFT + W` | Selector/Panel de fondos de pantalla de Noctalia |
| `SUPER + Z` | Panel de Configuración de Noctalia |
| `SUPER + X` | Panel del Centro de Control |
| `SUPER + .` | Selector de Emojis |
| `SUPER + L` | **L**ock / Bloquear pantalla |
| `SUPER + ALT + C` | Menú de Sesión (Apagar, reiniciar, suspender) |

---

### 🔊 Controles de Hardware

| Atajo / Tecla | Acción |
| :--- | :--- |
| `XF86AudioRaiseVolume` | Subir volumen |
| `XF86AudioLowerVolume` | Bajar volumen |
| `XF86AudioMute` | Silenciar salida de audio |
| `XF86AudioMicMute` | Silenciar micrófono |
| `XF86AudioPlay / Pause` | Reproducir / Pausar medios |
| `XF86AudioNext / Prev` | Siguiente / Anterior pista |
| `XF86MonBrightnessUp / Down` | Subir / Bajar brillo de pantalla |

---

### 🛠️ Utilidades y Capturas

| Atajo | Acción |
| :--- | :--- |
| `SUPER + P` | Selector de color en pantalla (`hyprpicker`) |
| `Print` | Captura de pantalla por región |
| `SUPER + Print` | Captura de pantalla completa |
| `SUPER + V` | Historial del Portapapeles de Noctalia |
| `SUPER + A` | Panel de Notificaciones |

---

### 📌 Workspaces (Espacios de Trabajo)

| Atajo | Acción |
| :--- | :--- |
| `SUPER + 1..0` | Ir al espacio de trabajo (1 al 10) |
| `SUPER + SHIFT + 1..0` | Mover ventana al espacio de trabajo (1 al 10) |
| `SUPER + S` | Mostrar / Ocultar Workspace Especial (Scratchpad) |
| `SUPER + SHIFT + S` | Mover ventana activa al Scratchpad |

---

## Instalación

```sh
git clone https://IIssO8II/my-noctalia-hyprland-config.git ~/.config/hypr
```
