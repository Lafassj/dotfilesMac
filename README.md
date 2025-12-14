# AeroSpace MacOS Config (Hyprland Style) 🍎

Configuración personalizada para **AeroSpace** en macOS, diseñada para usuarios que vienen de **Arch Linux + Hyprland** y buscan replicar el flujo de trabajo de un *Tiling Window Manager*.

Esta configuración utiliza atajos estilo Vim (HJKL), bordes visuales para el foco activo y una estética minimalista.

## 🛠 Herramientas utilizadas

* **Window Manager:** [AeroSpace](https://github.com/nikitabobko/AeroSpace)
* **Bordes:** [JankyBorders](https://github.com/FelixKratz/JankyBorders)
* **Terminal:** iTerm2
* **Fuente recomendada:** JetBrainsMono Nerd Font

## 🚀 Instalación

### 1. Instalar dependencias
Abre tu terminal y ejecuta los siguientes comandos para instalar todo lo necesario mediante Homebrew:

```bash
# Instalar AeroSpace (Tiling WM)
brew install --cask nikitabobko/tap/aerospace

# Instalar JankyBorders (Para bordes de colores)
brew tap FelixKratz/formulae
brew install borders

# Instalar iTerm2 (Si aún no la tienes)
brew install --cask iterm2

```
### 2. Crear directorio de configuración
Asegúrate de que la carpeta de configuración exista en tu sistema:

```bash
mkdir -p ~/.config/aerospace
```
### 3. Crear directorio de configuración
Clona este repositorio (o descarga el archivo aerospace.toml) y copia el archivo a la ruta de configuración:

```bash
cp aerospace.toml ~/.config/aerospace/aerospace.toml
```

