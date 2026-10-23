# Tokyo Ghoul Theme

Uno de tus temas personales para VS Code. La extensión cambia únicamente **colores**, nunca los iconos.

## Instalación en Arch Linux

1. Extrae este ZIP en `~/.vscode/extensions/`. Debe quedar la carpeta `~/.vscode/extensions/tokyo-ghoul-theme-0.1.0/`.
2. Reinicia VS Code o ejecuta `Developer: Reload Window`.
3. Abre **Preferences: Color Theme** (`Ctrl+K`, luego `Ctrl+T`) y selecciona **Tokyo Ghoul — One Eyed**.
4. Elimina `workbench.colorCustomizations` y `editor.tokenColorCustomizations` de tu archivo **User settings.json**, ya que sobreescriben los colores aportados por cualquier extensión de temas. Conserva `workbench.iconTheme` y todas las demás opciones.

## Para agregar más temas a la misma extensión

Duplica `themes/one-eyed-color-theme.json` con otro nombre, modifica sus colores y añade otro elemento al array `contributes.themes` del `package.json`, con otra etiqueta y la ruta al JSON nuevo. Después recarga VS Code. Todos tus temas aparecerán en el selector de colores.

## Nota

Este es un primer tema autónomo construido con los colores que definimos. Como antes estaba basado en Monokai Pro con ajustes encima, algunos colores secundarios o de sintaxis pueden diferir un poco; afínalos en el JSON del tema.
